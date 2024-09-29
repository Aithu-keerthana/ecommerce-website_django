Django eCommerce

This is a Django-based eCommerce platform that includes features like product management, user authentication, shopping cart, checkout process, and order management. The project also supports various product categories and a search functionality to enhance user experience.

Features

Product Management: Admin users can add, edit, and delete products.

User Authentication: Users can register, log in, and manage their accounts.

Shopping Cart: Users can add items to their cart and update quantities.

Checkout and Order Management: Users can complete purchases, and their orders are saved in the system.

Search Functionality: Users can search for products across different categories.

Mock Payment Gateway: A simple payment system that simulates the checkout process.


Installation

Follow the steps below to set up and run the project locally.

Prerequisites

Python 3.x

Django 3.x or above

pip (Python package installer)

Virtualenv (optional but recommended)


Setup Instructions

1. Clone the repository:

git clone https://github.com/zinmyoswe/Django-Ecommerce.git
cd Django-Ecommerce


2. Create a virtual environment (optional but recommended):

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`


3. Install dependencies:

pip install -r requirements.txt


4. Set up the database:

Run the following commands to set up the SQLite database and create necessary tables:

python manage.py migrate


5. Create a superuser (admin) for managing the eCommerce platform:

python manage.py createsuperuser


6. Run the development server:

Start the local development server to see the website:

python manage.py runserver

Visit http://127.0.0.1:8000/ in your browser to access the site.



Project Structure

The key folders and files are as follows:

ecommerce: The main Django project folder.

templates: Contains HTML templates for the website.

static: Contains static files like CSS and JavaScript.

bin: Scripts for managing the Django application.

requirements.txt: Lists all the dependencies required to run the project.


License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the project with attribution.

Contributing

Contributions are welcome! If you find any issues or have ideas for improvement, feel free to open an issue or create a pull request.
