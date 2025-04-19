---

# **Dimacard**

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/balvardi/dimacard/blob/main/LICENSE)
[![GitHub release](https://img.shields.io/github/v/release/balvardi/dimacard?include_prereleases)](https://github.com/balvardi/dimacard/releases)
[![GitHub issues](https://img.shields.io/github/issues/balvardi/dimacard)](https://github.com/balvardi/dimacard/issues)

**Dimacard** is a web-based application that allows users to create and send beautiful greeting cards for various occasions. The project includes features like user authentication, personalized messages, email delivery, and interactive animations.

Live Demo: [dimacard.ir](http://dimacard.ir)  
Author's Website: [dimagroup.ir](http://dimagroup.ir)

---

## **Features**

- **User Authentication**: Secure registration and login system for users.
- **Customizable Cards**: Users can create personalized greeting cards with custom messages.
- **Email Delivery**: Cards are sent to recipients via email with a unique link.
- **Interactive Animations**: Beautiful animations (e.g., balloons, confetti) enhance the user experience.
- **Responsive Design**: Fully responsive design for all devices (desktop, tablet, mobile).
- **Admin Panel**: Users can manage their created cards (view, edit, delete).

---

## **Screenshots**

### **1. Homepage**
![Homepage](assets/images/homepage.png)

### **2. Create Card Page**
![Create Card](assets/images/create_card.png)

### **3. View Card Page**
![View Card](assets/images/view_card.png)

---

## **Download**

You can download the latest version of Dimacard from the following link:

- [dimacard-v.1.0.0.beta.zip](https://github.com/balvardi/dimacard/blob/main/dimacard-v.1.0.0.beta.zip)

---

## **Installation**

### **Prerequisites**

Before you begin, ensure you have the following installed:

- PHP >= 7.4
- MySQL
- Composer (for PHPMailer)
- Web Server (e.g., Apache, Nginx)

### **Steps**

1. **Download the Project**
   - Download the ZIP file from the [latest release](https://github.com/balvardi/dimacard/blob/main/dimacard-v.1.0.0.beta.zip).
   - Extract the files to your desired directory.

2. **Install Dependencies**
   Install PHPMailer using Composer:
   ```bash
   composer install
   ```

3. **Set Up Database**
   - Create a new MySQL database.
   - Import the SQL schema from `database.sql` into your database.

4. **Configure Environment**
   Update the database connection details in `includes/db.php`:
   ```php
   $host = 'localhost';
   $dbname = 'dimacard_db';
   $username = 'root';
   $password = '';
   ```

5. **Run the Application**
   - Place the project files in your web server's root directory (e.g., `htdocs` or `www`).
   - Access the application via your browser (e.g., `http://dimacard.ir`).

---

## **Configuration**

### **SMTP Settings**
To enable email sending, configure SMTP settings in `send_card.php`:
```php
$mail->Host = 'smtp.example.com'; // Replace with your SMTP server
$mail->Username = 'your_email@example.com'; // Replace with your email
$mail->Password = 'your_password'; // Replace with your email password
```

---

## **Usage**

1. **Register/Login**: Create an account or log in to the system.
2. **Create a Card**: Fill out the form to create a personalized greeting card.
3. **Send the Card**: Enter the recipient's email and send the card.
4. **View the Card**: Recipients can view the card via the unique link sent to their email.

---

## **Release Notes**

### **v1.0.0-beta**
- Initial release of Dimacard.
- Added user authentication (login/register).
- Implemented card creation and email delivery.
- Included interactive animations using GSAP.
- Responsive design for all devices.

---

## **Contributing**

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Commit your changes (`git commit -m "Add some feature"`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Open a pull request.

Please ensure your code follows the project's coding standards and includes appropriate tests.

---

## **Support**

If you encounter any issues or have questions about Dimacard, feel free to open an issue on GitHub:

- [GitHub Issues](https://github.com/balvardi/dimacard/issues)

For general inquiries, you can contact us via email:

- Email: balvardi@dimagroup.ir

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Acknowledgments**

- [PHPMailer](https://github.com/PHPMailer/PHPMailer) for email functionality.
- [GSAP](https://greensock.com/gsap/) for animations.
- [Bootstrap](https://getbootstrap.com/) for styling.

---

## **Contact**

- **Author**: R.Balvardi  
- **Website**: [dimagroup.ir](http://dimagroup.ir)  
- **GitHub**: [balvardi](https://github.com/balvardi)  
- **Email**: balvardi@dimagroup.ir  

---
