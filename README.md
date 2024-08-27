# Hospital Management System (HMS)

## Overview
The Hospital Management System (HMS) is a comprehensive web-based application designed to manage and streamline the operations of a hospital. This system allows patients, doctors, and administrators to interact with the platform to handle various tasks such as booking appointments, managing patient information, and overseeing hospital operations.

## Features
- **Patient Management:** Patients can register, login, and book appointments with available doctors.
- **Doctor Management:** Doctors can login to their dashboard to manage appointments and patient information.
- **Admin Management:** The admin can manage the entire hospital operations, including patient records, doctor schedules, and other key aspects.
- **Contact Us Form:** Users can submit their contact information and queries through a contact form, which gets stored in the database.
- **Responsive Design:** The application is fully responsive, making it accessible on different devices like desktops, tablets, and smartphones.

## Technologies Used
- **Frontend:** HTML5, CSS3, Bootstrap, JavaScript
- **Backend:** PHP
- **Database:** MySQL
- **Version Control:** Git & GitHub

## Installation Instructions
Follow these steps to get the Hospital Management System up and running on your local machine:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/avinashyadavofficial/HMS.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd HMS
    ```

3. **Set up the database:**
    - Import the SQL file located in the `hms/include` directory into your MySQL database.
    - Update the `config.php` file in the `hms/include` directory with your database credentials.

4. **Run the application:**
    - Place the project folder in your web server's root directory (e.g., `htdocs` for XAMPP).
    - Start your local server (e.g., XAMPP, WAMP).
    - Access the application via your browser: `http://localhost/HMS`

## Usage
- **Home Page:** Provides a brief introduction to the hospital and key features.
- **Logins:** Separate login sections for Patients, Doctors, and Admins.
- **Services:** Lists the key medical services offered by the hospital.
- **Gallery:** Displays images showcasing the hospital facilities.
- **Contact Us:** Users can reach out to the hospital through a contact form.

## Screenshots
![Home Page](assets/images/screenshot1.png)
![Login Page](assets/images/screenshot2.png)
![Contact Form](assets/images/screenshot3.png)

## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
- Bootstrap for responsive design components.
- Font Awesome for icons.

## Contact
For any inquiries or feedback, please reach out to me at avinashyadavofficial@gmail.com.
