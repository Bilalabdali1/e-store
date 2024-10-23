Book Haven
Overview
Book Haven is a full-featured e-commerce platform built for book lovers to browse, search, and purchase books online. The application provides a seamless and secure online shopping experience with features like sorting, filtering, personalized recommendations, and a responsive design that works across devices. Whether you're looking for a specific title or want to explore new genres, Book Haven delivers a smooth user experience.

Features
Book Catalog: Browse through a vast collection of books with options to sort by price, genre, ratings, and alphabetical order.
Search Functionality: Easily search for books using keywords and discover new titles.
Personalized Recommendations: Receive book suggestions based on your browsing and purchasing history.
Cart & Checkout: Add books to the cart, view a side-cart summary, and proceed to secure checkout using Stripe API for payments.
User Authentication: Secure sign-up and login features with role-based access control for admin functionality.
Admin Dashboard: Manage the book inventory, add or remove books, and monitor customer activity.
Mobile Responsive: Enjoy a responsive interface optimized for all devices, ensuring a consistent user experience across mobile and desktop.
Technologies Used
Frontend: React.js, RESTful API integration
Backend: Node.js, Express.js
Database: MySQL with Sequelize ORM
Payment Processing: Stripe API for secure payments
Testing: Postman for API testing
Deployment: Localhost for development, attempted Vercel for frontend deployment
Installation
Follow these steps to set up the project locally:

Clone the repository:
bash
Copy code
git clone https://github.com/Bilalabdali1/Book-Haven.git
Navigate to the project directory:
bash
Copy code
cd book-haven
Install the necessary dependencies:
bash
Copy code
npm install
Configure your .env file with MySQL database credentials and Stripe API keys.
Start the backend server:
bash
Copy code
npm run server
Start the frontend application:
bash
Copy code
npm start
Usage
Once the app is running locally, visit the website at http://localhost:3000 to start exploring the Book Haven store. You can browse books, filter through categories, add items to your cart, and make secure purchases.

Admin credentials for testing:

Email: billy@gmail.com
Password: 12345678
App Preview
Home Page

Book Details

Admin Dashboard

Challenges and Learning
Deployment: We faced challenges with deploying the full application due to limitations with free hosting platforms. While the frontend was successfully hosted on Vercel, the backend deployment was restricted due to server-side limitations. For demonstration purposes, the project runs on localhost.

Backend & Frontend Integration: Synchronizing the frontend and backend operations was challenging, but working through RESTful API integration was a great learning experience.

Future Improvements
Deploy the full stack on a cloud platform with complete backend integration.
Implement additional user features like wishlists, user reviews, and book recommendations based on ratings.
Optimize for performance with larger datasets.
