# TODO

- **Add and Drop**:
  - The add and drop page should only include courses offered by the department head.
  - Add and drop date should be restricted by the school calendar.
- **Auto generate username and password when adding students and lecturers**
  - Instead of filling the username and password for the student/lecturer, the system should automatically generate them and send to the student's/lecturer's email.
- **Payment integration**:
  - Integrating PayPal and Stripe for students to pay their fees.
- **Integrate the dashboard with dynamic/live data**:
  - Overall attendance
  - School demographics
      - Lecturer qualification
      - Students' level
  - Students average grade per course:
    This helps to keep track of students' performance
  - Overall Course Resources
    - Total number of videos, courses, documentation
  - Event calendar:
    - A calendar that shows upcoming events
  - Enrollments per course
    - How many students enroll in each course
  - Website traffic over a specific user type (Admin, Student, Lecturer, etc.)
- **Apply Filtering for all tables**:
  - This can be done using `django-filter` and other jQuery libraries
- **Apply data exporting for all tables**:
  - This can be done using jQuery libraries like `DataTables`
- **Using a template to PDF converter to generate reports**:
  - This can be done using the popular package `xhtml2pdf`
