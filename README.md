# effective-octo-computing-machine
Online Eyewear System
Introduction
The Online Eyewear System is a web application developed using Python with the Django framework, HTML, CSS, and JavaScript. This system allows users to browse, select, and purchase eyewear products online. It includes features for managing products, user accounts, shopping carts, and orders.

Features
User Authentication
User Registration: Users can create an account by providing their details.
User Login: Registered users can log in with their credentials.
Password Reset: Users can reset their password in case they forget it.

Product Catalog
Browse Products: Users can view eyewear products in different categories.
Product Details: Detailed product information is available, including images, price, and description.

Shopping Cart
Add to Cart: Users can add eyewear products to their shopping cart.
Edit Cart: Users can adjust the quantity or remove items from the cart.
Checkout: Users can proceed to the checkout process.

Ordering
Order Placement: Users can place orders for the items in their cart.
Order History: Users can view their past orders and order status.
Payment Integration: Payment options for online transactions.

Admin Panel
Product Management: Admins can add, edit, and remove products from the catalog.
Order Management: Admins can view and manage user orders.
User Management: Admins can manage user accounts.

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/eyewear-system.git

Navigate to the project directory:
bash
Copy code
cd eyewear-system

Create a virtual environment and activate it:
bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'

Install project dependencies:
Copy code
pip install -r requirements.txt

Run database migrations:
Copy code
python manage.py migrate

Create a superuser for admin access:
Copy code:
python manage.py createsuperuser

Start the development server:
Copy code:
python manage.py runserver
Access the application in your web browser at http://127.0.0.1:8000//.

Configuration:
Update the settings.py file to configure the database, static and media file storage, and other settings.

Usage:
Register as a new user or use the admin account to add products and manage the system.
Use the website to browse eyewear products, add them to your cart, and place orders.

Dependencies:
Python
Django
HTML
CSS
JavaScript

License:
This project is licensed under the MIT License - see the LICENSE file for details.

Contributors:
Dhanush Kumar

Acknowledgments:
libraries:Pillow
framework:Django

Contact:
For support or inquiries, contact : dhanushkumar1707@gmail.com
