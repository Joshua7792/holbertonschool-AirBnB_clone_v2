# Flask Web Application Tasks

This document outlines a series of tasks for building and running Flask web applications.

## 0. Hello Flask!

- **Description**: Write a script that starts a Flask web application.
- **Requirements**:
  - The application must listen on `0.0.0.0`, port `5000`.
  - Define a route `/` to display "Hello HBNB!".
  - Use `strict_slashes=False` in your route definition.
- **Repository**: holbertonschool-AirBnB_clone_v2
- **Directory**: web_flask
- **File**: `0-hello_route.py`, `__init__.py`

## 1. HBNB

- **Description**: Modify the Flask web application.
- **Requirements**:
  - Add a new route `/hbnb` to display "HBNB".
- **Repository**: holbertonschool-AirBnB_clone_v2
- **Directory**: web_flask
- **File**: `1-hbnb_route.py`

## 2. C is fun!

- **Description**: Expand the Flask web application.
- **Requirements**:
  - Add a new route `/c/<text>` to display "C " followed by the value of `text` (replace underscore `_` symbols with a space).
- **Repository**: holbertonschool-AirBnB_clone_v2
- **Directory**: web_flask
- **File**: `2-c_route.py`

## 3. Python is cool!
- **Description**: Improve the Flask web application with Python features.
- **Requirements**:
  - Add a new route `/python/<text>` to display "Python " followed by the value of `text` (replace underscore `_` symbols with a space).
  - Define a default value of `is_cool` to be "is cool".
- **Repository**: holbertonschool-AirBnB_clone_v2

## 4. Is it a number?
- **Description**: Make sure all inputs are numbers before processing them. If not, return an error message.
- **Requirements**:
  - Add a new route `/number/<n>` to display "n is a number" only if `n` is an integer.
- **Repository**: holbertonschool-AirBnB_clone_v2

## 5. Number template
- **Description**: Improve the Flask web application with HTML templates.
- **Requirements**:
  - Add a new route `/number_template/<n>` to display an HTML page only if `n` is an integer.
  - Use the `templates/5-number.html` template to display the number.

## 6. Odd or even?
- **Description**: Improve the Flask web application with HTML templates.
- **Requirements**:
  - Add a new route `/number_odd_or_even/<n>` to display an HTML page only if `n` is an integer.
  - Use the `templates/6-number_odd_or_even.html` template to display the number.

## 7. Improve engines
- **Description**: Improve the Flask web application with database storage.
- **Requirements**:
  - Update `FileStorage` to work with DBStorage.
  - Update `__init__.py` to use `DBStorage` by default.
  - Update `index.html` to display the number of `State` and `City` objects in storage.

## 8. List of states
- **Description**: Write a script for a Flask web application with more complex rendering.
- **Requirements**:
  - Implement `/states_list` to display an HTML page like `7-index.html`.
  - Copy necessary CSS and image files to the appropriate directories.
  - Load `State` objects from DBStorage and sort them by name.

## 9. Cities by states
- **Description**: Write a script for a Flask web application with more complex rendering.
- **Requirements**:
  - Implement `/cities_by_states` to display an HTML page like `8-cities_by_states.html`.
  - Copy necessary CSS and image files to the appropriate directories.
  - Load `State` and `City` objects from DBStorage and sort them by name.

## 10. States and State
- **Description**: Write a script for a Flask web application with more complex rendering.
- **Requirements**:
  - Implement `/states` and `/states/<id>` to display an HTML page like `9-states.html`.
  - Copy necessary CSS and image files to the appropriate directories.
  - Load `State` and `City` objects from DBStorage and sort them by name.

## 11. HBNB filters

- **Description**: Write a script for a Flask web application with more complex rendering.
- **Requirements**:
  - Implement `/hbnb_filters` to display a complex HTML page like `6-index.html`.
  - Copy necessary CSS and image files to the appropriate directories.
  - Load State, City, and Amenity objects from DBStorage and sort them by name.
- **Repository**: holbertonschool-AirBnB_clone_v2
- **File**: `10-hbnb_filters.py`, `templates/10-hbnb_filters.html`

### Resources

- [What is a Web Framework?](#)
- [Flask Documentation](#)
- [Jinja Template Documentation](#)

### Learning Objectives

- Understanding of web frameworks.
- Building a web framework with Flask.
- Defining routes in Flask.
- Creating dynamic templates.
- Displaying data from a MySQL database in HTML.

### Requirements

#### Python Scripts

- Use Python 3.8.5.
- Follow PEP 8 style guidelines.
- All files must end with a new line.
- All modules, classes, and functions must include documentation.

#### HTML/CSS Files

- All files should end with a new line.
- Follow W3C validation standards.
- Store CSS files in the `styles` folder and images in the `images` folder.
- Avoid the use of `!important` and IDs in CSS.
