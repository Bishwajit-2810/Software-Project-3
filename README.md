# E-commerce Website

Welcome to the E-commerce Website repository. This project is built using PHP, HTML, and CSS to provide a robust platform for online shopping. Below, you’ll find setup instructions, information about the project, and placeholders for additional resources like screenshots and hosted website links.

---

## Features

- User authentication (sign-up, login, logout)
- Product listing with categories
- Shopping cart functionality
- Order management
- Admin panel for managing products and orders
- Responsive design for mobile and desktop users

---

## Local Setup

Follow these instructions to set up the project locally using XAMPP.

### Prerequisites

1. XAMPP installed on your system ([Download XAMPP](https://www.apachefriends.org/index.html))
2. PHP version 7.4 or higher
3. Basic understanding of PHP and database management

### For Arch Linux

1. Give write permission to the `htdocs` folder:

   ```bash
   sudo chmod -R 777 /opt/lampp/htdocs
   ```

2. Install XAMPP:

   ```bash
   paru -Syu xampp
   ```

   Alternatively, download the package from [Apache Friends](https://www.apachefriends.org/index.html) and follow the installation instructions.

3. Start XAMPP:

   ```bash
   sudo /opt/lampp/lampp start
   ```

4. Clone this repository into the `htdocs` folder:

   ```bash
   cd /opt/lampp/htdocs
   git clone https://github.com/Bishwajit-2810/Software-Project-3.git
   ```

5. Configure the database:

   - Open phpMyAdmin ([http://localhost/phpmyadmin](http://localhost/phpmyadmin)).
   - Create a new database (e.g., `ecommerce`).
   - Import the provided SQL file located in the `database` folder of the repository.

6. Update the configuration:

   - Open the `config.php` file.
   - Update the database credentials as per your setup.

7. Access the website:

   - Navigate to [http://localhost/ecommerce%20website/home.php](http://localhost/ecommerce%20website/home.php) in your browser.

### For Windows

1. Give write permission to the `htdocs` folder (if required):

   - Right-click on the `htdocs` folder (default: `C:\xampp\htdocs`).
   - Select `Properties` > `Security` > `Edit`.
   - Grant `Full Control` to the appropriate user.

2. Install XAMPP from [Apache Friends](https://www.apachefriends.org/index.html).

3. Start XAMPP:

   - Open the XAMPP Control Panel.
   - Start the `Apache` and `MySQL` modules.

4. Clone this repository into the `htdocs` folder:

   - Navigate to the XAMPP installation directory (default: `C:\xampp\htdocs`).
   - Clone the repository:

     ```bash
     git clone https://github.com/username/ecommerce-website.git
     ```

5. Configure the database:

   - Open phpMyAdmin ([http://localhost/phpmyadmin](http://localhost/phpmyadmin)).
   - Create a new database (e.g., `shop_db`).
   - Import the provided SQL file located in the `database` folder of the repository.

6. Update the configuration:

   - Open the `config.php` file in a text editor.
   - Update the database credentials as per your setup.

7. Access the website:

   - Navigate to [http://localhost/ecommerce%20website/home.php](http://localhost/ecommerce%20website/home.php) in your browser.

---

## Screenshots

Include screenshots of the website to showcase its features and design. Add them in the `screenshots` folder of the repository and reference them here.

![Homepage Screenshot](/screenshots/homepage.png)
![Category Screenshot](/screenshots/catagory.png)
![Products Screenshot](/screenshots/products.png)
![Admin Panel Screenshot](/screenshots/admin-panel.png)
![Admin Products Screenshot](/screenshots/admin_products.png)

### Example

---

## Hosted Website

If the project is hosted online, provide the link here:

[Visit the E-commerce Website](http://ecommerce14141417.infinityfreeapp.com/)

---

## Contributing

1. Fork the repository.
2. Create a new branch for your feature/bugfix.
3. Commit your changes with descriptive messages.
4. Submit a pull request for review.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

For any queries or feedback, feel free to contact the project maintainer at [bishwajit2810@gmail.com](mailto:bishwajit2810@gmail.com).
