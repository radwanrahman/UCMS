# University Course Management System (UCMS)

A web-based platform for managing university courses, assignments, and announcements.

## Prerequisites
- **XAMPP** (or any PHP/MySQL environment)
- Web Browser

## Installation & Setup

1.  **Place Files**: Ensure this project folder `UCMS` is inside your XAMPP `htdocs` directory (e.g., `D:\xampp\htdocs\UCMS`).
2.  **Start Server**: Open **XAMPP Control Panel** and start **Apache** and **MySQL**.
3.  **Database Setup**:
    - Open your browser and go to [http://localhost/phpmyadmin](http://localhost/phpmyadmin).
    - Create a new database named `ucms`.
    - Import the `database.sql` file located in the project folder.
    - *Note*: If your MySQL `root` user has a password, update `config/db.php`.

## How to Run

1.  Open your web browser.
2.  Go to: **[http://localhost/UCMS](http://localhost/UCMS)**
3.  You will see the landing page.

## Usage

- **Register**: Create a new account. You can choose to be a **Student** or a **Teacher**.
- **Teacher**:
    - Create a new course to get a **Course Code**.
    - Share the code with students.
    - Post announcements in the course stream.
- **Student**:
    - Use a **Course Code** to join a class.
    - View announcements and course details.
# UCMS
