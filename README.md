# Cedrick Balagtas 312 - Activity 4
This project was created for Activity 4 in the IS 312 course. It demonstrates how to build a simple RESTful API using Python and Flask to manage products and orders. The application uses a SQLite database to perform basic CRUD operations and returns data in JSON format, which can be tested using Postman.
## Framework Used
Flask – a lightweight Python web framework used to create RESTful APIs, handle routes, and run a local server. It works with additional libraries like SQLAlchemy for database operations and Marshmallow for handling JSON data.
### How to Run the Application Locally
1. Open the "Balagtas_ecommerce_app" folder
2. Open the project "app.py" in Pycharm
3. install flask with additional libraries
```
pip install flask
```
```
pip install flask flask-sqlalchemy marshmallow 
```
4. Run the app.py file, it should give you a URL
5. In postman, put the URL (http://127.0.0.1:5000)
6. Test /products & /orders in Postman
