# Automated Testing for Flipkart E-Commerce Platform

## About the Project

This project implements automated testing for the Flipkart e-commerce website using Selenium with pytest. The following test cases are covered:

- *Flipkart Home Page validation:* Validates the Flipkart main page
- *Flipkart Login Page validation:* Validates the login page
- *Mobile Page:* Search for mobile and validates, adding to cart page and validates in cart page
- *Book Page:* Search for book and validates, adding to cart page and validates in cart page
- *Adapter Page and Pincode Verification:* Validates user searching the adapter from the cart page and selects the adapter and verify with pincode and adding to cart
- *Price Confirmation:* Validates the price of all the products in the cart page


## How to Clone the Repository

To clone this repository, use the following command:
```
git clone git clone https://github.com/mvbharath66/Flipkart_Selenium_Pytest_Project.git
```

## Creation of Virtual Environment
It's recommended to use a virtual environment to manage dependencies. To create a virtual environment, navigate to your project directory and run:


```
python -m venv venv
```
Activate the virtual environment:

- Windows: venv\Scripts\activate
- Linux/Mac: source venv/bin/activate

## Installation of Requirements
Install the required packages using the following command:

```
pip install -r requirements.txt
```

## How to Run Tests
To execute the tests, use the following command:
```
pytest 
```
Another way to run, it will generate the report in html format
```
pytest --html=report.html
```

#### Contact
For any questions or issues, please contact:

Name: M V Bharath

Email: mvbharath66@gmail.com

# Automated Testing for Flipkart E-Commerce Platform