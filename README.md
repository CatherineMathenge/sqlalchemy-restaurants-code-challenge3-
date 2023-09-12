# sqlalchemy-restaurants-code-challenge3-
# Restaurant Review Database
The Restaurant Review Database is a straightforward application for users to review and manage their preferred restaurants. This project relies on SQLAlchemy and Python.

# Prerequisites
Before you begin, make sure you meet these requirements:

Python 3.6 or a later version is installed on your computer.
The SQLAlchemy library is installed. You can install it using pip.
Installation
Clone this repository to your local machine:

Navigate to the project directory.

Optionally, create a virtual environment (recommended).

Activate the virtual environment.

Install the project dependencies.

# Usage
You can use the restaurant_reviewer module to interact with the Restaurant Review Database in your Python script.

# Database Structure
The database comprises three main tables:

restaurants: Stores restaurant information, including id, name, and price.
customers: Contains customer details such as id, first_name, and last_name.
reviews: Holds reviews with attributes like id, star_rating, restaurant_id, and customer_id. It establishes relationships between customers, restaurants, and reviews.
To populate the database with sample data, run:

# Contributing
We welcome contributions to this project! If you'd like to contribute, please follow the guidelines outlined in the CONTRIBUTING file.

# License
This project is licensed under the MIT License. For more information, see the LICENSE file.
