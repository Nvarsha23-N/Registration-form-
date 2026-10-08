# Student Registration Form

A simple student registration web page built with HTML, CSS, and JavaScript. Students enter their personal and academic details, and the data is saved in the browser using `localStorage`. After registering, the student can continue to a login page.

## Features

- Collects personal, contact, and academic details
- Required-field validation using HTML5
- Email, phone, and date input types for basic format checks
- Gender selection using radio buttons
- Department and course selection using dropdowns
- Optional student photo upload (image files only)
- Saves registration data in the browser's `localStorage`
- Success message with a **Login** button after registering

## Tech Stack

- HTML5
- CSS3
- JavaScript (Vanilla)

## Form Fields

| Field          | Input Type     | Required |
|----------------|----------------|----------|
| Roll No.       | Text           | Yes      |
| Student Name   | Text           | Yes      |
| Father's Name  | Text           | Yes      |
| Date of Birth  | Date           | Yes      |
| Mobile No.     | Tel            | Yes      |
| Email ID       | Email          | Yes      |
| Password       | Password       | Yes      |
| Gender         | Radio          | Yes      |
| Department     | Dropdown       | Yes      |
| Course         | Dropdown       | Yes      |
| Student Photo  | File (image)   | No       |
| City           | Text           | Yes      |
| Address        | Textarea       | Yes      |

**Departments:** CSE, IT, ECE, Civil, Mech
**Courses:** B.Tech, M.Tech, MCA, MBA

## Project Structure

```
student-registration-form/
├── index.html     # Registration form
├── style.css      # Styling
├── login.html     # Login page (opened after registration)
└── README.md
```

## Getting Started

1. Clone the repository:
```bash
   git clone https://github.com/your-username/student-registration-form.git
```
2. Go to the project folder:
```bash
   cd student-registration-form
```
3. Open `index.html` in your browser.

## How It Works

1. The student fills in all the required fields.
2. On clicking **Register**, the form data is stored in `localStorage` under the key `student`.
3. The form is hidden and a "Registration Successful!" message appears.
4. Clicking **Login** redirects to `login.html`.

## Notes

- Data is stored only in the user's browser, not on a server.
- The password is stored as plain text in `localStorage`, so this is for learning/demo purposes only and should not be used in production.
- The uploaded photo is not saved with the registration data.

## Future Improvements

- Connect to a backend (Node.js, PHP, or Python) and a database
- Hash passwords before storing them
- Add stronger validation (mobile number length, password strength)
- Save and display the student photo
- Add a confirm-password field

## Contributing

Contributions are welcome! Fork the repo and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Author

**Your Name**
GitHub: [@your-username](https://github.com/your-username)
