# NewEcommerceApp

A feature-rich Django-based application.
This application allows users to browse, search, and purchase products from various categories offered by registered vendors. It also provides functionalities for vendors to manage their inventory, process orders, and track sales.

Installation Prerequisites:
Python 3.x,
Django framework,
MySQL database, 
Pillow Library for image Processing,

Installation Instructions:
Clone the repository:
Bash
git clone https://github.com/Ajuleta/newecommerceapp.git

content_copy
Install dependencies:
Bash
cd NewEcommerceApp
pip install -r requirements.txt
Use code with caution.
content_copy
Set up database:
Follow instructions on how to set up MySQL database from mysql.com.
Update settings.py with your database connection details.
Migrate models:
Bash
python manage.py migrate

Create a superuser account for administrative access:
Bash
python manage.py createsuperuser

Run the application:
Bash
python manage.py runserver

Configuration
Update settings.py with your preferred configurations like email settings, secret keys, and payment gateway credentials.

User Features:
Product browsing: Explore a wide range of products categorized for easy navigation,
Search functionality: Find specific products using keywords or filters,
Product details: View detailed product descriptions, images, and vendor information,
Shopping cart: Add and manage items for purchase,
Secure checkout: Process orders securely using a payment gateway integration,
Order tracking: Track the status of placed orders,
User account management: Create accounts, view order history, and update profiles,
Wishlist functionality: Save desired products for later purchase,
Review and rating system: Leave reviews and ratings for products and vendors,

Vendor Features:
Vendor registration and login: Create and manage vendor accounts,
Product addition and management: Add, edit, and manage product listings,
Inventory control: Track product stock levels and set reorder points,
Order processing: View, manage, and fulfill customer orders,
Sales reporting: Track sales performance and generate reports,
Vendor profile management: Update vendor information and contact details,

Contributing
We welcome contributions to improve this application! Please refer to the CONTRIBUTING.md file for guidelines on submitting bug reports, feature requests, and pull requests.

Authors
Opio Kenneth Gavin
Contact
Phone +256772229556, email. gavinopio256@gmail.com 
