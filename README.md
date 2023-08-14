# Electrify - An E-Commerce Fullstack Website

"Electrify" is a dynamic e-commerce platform that merges Django backend capabilities with React frontend interactivity. It offers a seamless online gadget shopping experience with features like product filters, sorting, user authentication, and a user-friendly interface.

## Technologies Used

### Backend

- Django: A high-level Python web framework for building robust and scalable backend applications.
- Django Rest Framework (DRF): A powerful toolkit for building Web APIs in Django applications.
- Simple JWT: A library for handling JSON Web Tokens (JWT) authentication in Django applications.
- Corsheaders: A Django middleware for handling Cross-Origin Resource Sharing (CORS).

### Frontend

- React: A JavaScript library for building user interfaces, providing a dynamic and interactive frontend.
- React Material-UI: A popular UI framework that offers a set of ready-to-use components with a modern design.
- React Bootstrap: A CSS framework for creating responsive and customizable user interfaces.
- Redux Toolkit: A library for efficient state management in React applications.
- Axios: A promise-based HTTP client for making API requests.

### Database

- SQLite (Development): A lightweight, file-based database for development and testing.
- PostgreSQL (Production): A powerful open-source relational database management system.

### Payment Integration

- PayPal API: Integration of the PayPal API for secure and seamless payment processing.

### Version Control

- Git: A distributed version control system for tracking changes in code.
- GitHub: A web-based platform for hosting Git repositories and collaborating with others.

## Features

- Product Listing: Display products in a grid or list view, including product name, price, and image.
- Sorting and Filtering: Allow users to sort products by price and filter based on categories.
- Detailed Product Pages: Provide detailed information about each product, including descriptions, ratings, and reviews.
- User Authentication: Implement a secure user authentication system using JSON Web Tokens (JWT).
- Login and Sign-Up: Provide user-friendly login and sign-up forms for account creation and authentication.
- Shopping Cart: Enable users to add and remove products from their shopping cart.
- Order History: Allow users to view their order history and order details.
- Secure Payment: Integrate PayPal API for secure payment processing during checkout.
- Responsive Design: Create a responsive user interface for a seamless experience on all devices.

## Installation and Setup

### Backend

1. Navigate to the `backend` folder:  cd backend




2. Create a virtual environment and activate it: 

python -m venv venv

source venv/bin/activate # On Windows: venv\Scripts\activate

3. Install the required packages:  pip install -r requirements.txt


4. Run migrations:  python manage.py migrate



5. Start the Django development server:   python manage.py runserver



### Frontend

1. Navigate to the `frontend` folder:  cd frontend


2. Install the required packages:  npm install


3. Start the React development server: npm start




## Usage

1. Visit the URL provided by the Django development server for the backend and React development server for the frontend to access the Electrify e-commerce platform.

2. Use the login and sign-up functionality to create an account and authenticate. After logging in, you'll have access to user-specific features such as the shopping cart and order history.

## Contributors

- [Your Name](https://github.com/popzon99)

Feel free to fork the repository and contribute to the project. If you encounter any issues, please submit them in the [Issues](https://github.com/popzon99/Ecommerce_store/issues) section.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.










 
