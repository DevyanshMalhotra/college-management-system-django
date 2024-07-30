# College Management System - Django

## Project Overview

The **College Management System** is a comprehensive web application built using Django, designed to streamline and manage college operations efficiently. It provides three distinct dashboards for different user roles—Admin/HOD, Teachers, and Students—each with specific privileges and functionalities to enhance the college management experience.

## Features

### Admin/HOD Dashboard
- **Home**: Overview of dashboard activities.
- **Update Profile**: Modify admin profile information.
- **Course Management**: Add, edit, and manage courses.
- **Subject Management**: Add, edit, and manage subjects.
- **Session Management**: Create and manage academic sessions.
- **Add Staff**: Add new staff members to the system.
- **Manage Staff**: View and update staff details.
- **Add Student**: Register new students.
- **Manage Student**: View and manage student details.
- **Notify Staff**: Send notifications to staff members.
- **Notify Student**: Send notifications to students.
- **View Attendance**: Review student attendance records.
- **Student Feedback**: Manage and review student feedback.
- **Staff Feedback**: Manage and review staff feedback.
- **Staff Leave**: Review and manage staff leave requests.
- **Student Leave**: Review and manage student leave requests.

### Teacher Dashboard
- **Home**: Overview of dashboard activities.
- **Update Profile**: Modify teacher profile information.
- **Add Result**: Record and manage student results.
- **Edit Result**: Edit previously recorded student results.
- **Take Attendance**: Mark attendance for classes.
- **View/Update Attendance**: View and update attendance records.
- **View Notifications**: Check notifications relevant to the teacher.
- **Apply For Leave**: Submit leave requests.
- **Feedback**: Provide feedback for students and administrative processes.
- **Live Student Defaulter List**: View a list of students with attendance below 75%.

### Student Dashboard
- **Update Profile**: Modify student profile information.
- **View Attendance**: Check personal attendance records.
- **View Notifications**: Receive and review notifications.
- **Apply For Leave**: Submit leave requests.
- **Feedback**: Provide feedback on college services.

## Installation

Follow these steps to set up the College Management System on your local machine:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/DevyanshMalhotra/college-management-system-django.git
    cd college-management-system-django
    ```

2. **Set Up Virtual Environment**

    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Apply Migrations**

    ```bash
    python manage.py migrate
    ```

5. **Run the Development Server**

    ```bash
    python manage.py runserver
    ```

Open your browser and navigate to [http://127.0.0.1:8000](http://127.0.0.1:8000) to access the application.

## Usage

- **Admin/HOD**: Log in as an admin to manage courses, subjects, sessions, staff, and students. Access various administrative functions from the admin dashboard.
- **Teacher**: Log in as a teacher to manage class results, attendance, and view notifications. Use the teacher dashboard to interact with the system.
- **Student**: Log in as a student to view personal attendance, notifications, and submit leave requests.

## Contributing

We welcome contributions to enhance the College Management System. To contribute:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Django - The web framework used.
- Bootstrap - For the styling and responsive design.
- FontAwesome - For icons.

For any issues or inquiries, please open an issue on the GitHub repository.
