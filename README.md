# Shihab-eCommerce  
A Django-Based E-Commerce Website  

## Project Overview  
Shihab-eCommerce is a fully functional e-commerce platform built using Django. The project includes user authentication, a shopping cart, checkout processing, and PayPal payment integration.  

## Features  
- User authentication (Login/Register)  
- Product listing with images and descriptions  
- Shopping cart functionality  
- Checkout process with shipping details  
- Secure payment integration with PayPal  
- Guest checkout with cookies  

## Project Structure  

### **1 | Project Setup & Templates**  
- Configure Django app  
- Set up templates and static files  
- Implement views & URLs  
- Design main layout and navigation  

### **2 | Data Structure**  
- Define models for products, orders, and users  
- Render product listings dynamically  
- Implement product image fields  
- Manage user-specific shopping carts  

### **3 | Site Functionality**  
- Add, update, and remove items from the cart  
- Collect shipping addresses  
- Create an order and process transactions  

### **4 | Guest Checkout**  
- Store cart data using cookies  
- Render cart totals for guest users  
- Handle guest orders effectively  

### **5 | Payment Integration**  
- Implement PayPal payment buttons  
- Set up a PayPal sandbox account for testing  
- Process payments securely  

## Installation  
1. Clone the repository:  
   ```sh
   git clone https://github.com/shihab173066/Shihab-eCommerce.git
   cd Shihab-eCommerce
   ```  
2. Create a virtual environment and install dependencies:  
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```  
3. Run the Django server:  
   ```sh
   python manage.py runserver
   ```  

## Technologies Used  
- **Backend**: Django, Python  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: SQLite (can be replaced with PostgreSQL or MySQL)  
- **Payment Gateway**: PayPal  

## Contributing  
Contributions are welcome! Feel free to submit issues or pull requests.  

## License  
This project is open-source under the MIT License.  