# Amazon Clone 
An Amazon e-commerce website clone developed using HTML, CSS, Python, and Django Framework. This project replicates the core features of an e-commerce platform, providing a simplified user interface and backend functionality.

# 🌟 Features
User Authentication: Register, login, and logout functionality for users.
Product Listing: Dynamic display of products with details like price, description, and ratings.
Add to Cart: Add products to the cart for easy checkout.
Search Products: A search bar to help users find specific items quickly.
Responsive Design: Optimized for both desktop and mobile devices.
Admin Panel: Manage products, users, and orders via the Django admin interface.

# 💻 Tech Stack
#Frontend
HTML5: Markup for structuring the website.
CSS3: Styling for responsive and aesthetic design.

#Backend
Python: Backend logic implementation.
Django Framework: MVC architecture for web application development.

#Database
Django’s default SQLite database. (Can be switched to a relational database like PostgreSQL or MySQL)

# 📂 Project Structure

amazon-clone/
├── amazon_clone/           # Main Django project folder. <br>
│   ├── settings.py         # Project settings. <br>
│   ├── urls.py             # URL configuration. <br>
│   └── wsgi.py             # WSGI entry point. <br>
├── app/                    # Main app for managing website logic. <br>
│   ├── migrations/         # Database migrations. <br>
│   ├── templates/          # HTML files for views. <br>
│   ├── static/             # CSS, JS, images, and other static files. <br>
│   ├── views.py            # View functions. <br>
│   ├── models.py           # Database models. <br>
│   └── urls.py             # App-specific URL patterns. <br>
└── manage.py               # Django management script. <br>


# 🛠 Future Improvements
**Payment Integration:** Add functionality for real transactions.
**Order Tracking:** Enable users to track their orders in real-time.
**Recommendations:** Suggest products based on user activity.
