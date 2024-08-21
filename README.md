# imenu
Intelligent Menu and Order System

## Project Overview: Restaurant Menu System

### Objective: 
Develop a Restaurant Menu System named imenu.ca, utilizing React, Node.js, and Firebase. The system aims to enhance the customer dining experience by offering an intuitive and interactive platform where users can browse the menu, place orders, and make payments online. The platform will display dish thumbnails, titles, prices, tags, and star ratings, with a powerful search feature to help users find their desired dishes quickly.

### Key Features and Functionality:
1. User Registration and Authentication
- Registration: Users can sign up with email and password, using Firebase Authentication for user management.
- Login: With Firebase Authentication handling session management, users can log in using their email and password.
- Logout: Users can log out, which ends their Firebase session.
- Support for social login options like Google and Facebook.
- Profile management for users to view and edit their personal information.
2. Dishes Management:
- Front-end: Dynamic display of dish thumbnails with titles, prices, tags, and star ratings.
- Backend: Management for adding, editing, and removing dishes.
- Searching: Search keywords and using categorization or tagging of dishes for easy browsing and filtering.
3. Ordering and Cart
- Cart page: Easy-to-navigate cart page with the option to modify the quantity or remove items.
- Checkout: Streamlined order process from cart to checkout.
- Payment: Integration with payment gateways for secure transactions.
4. Likes and Comments
- Likes: A rating system to capture and display user feedback
- Comment Posts: Users can like dishes and leave comments, helping others make informed choices.
5. Admin Panel
- Interface: A robust admin interface for managing dishes, orders, user comments, and system settings.
- Visualization: Real-time analytics and reporting features to monitor sales and user engagement.
6. Firebase Integration
- Firebase Authentication: For user authentication and management.
- Firebase Realtime Database or Firestore: Real-time database and cloud storage for storing user data, order details, and dish images. 


### Technical Details:
1. Technology Stack:
- Frontend: React.js with Material-UI for responsive and accessible user interfaces.
- Backend: Node.js with Express for server-side logic and API management.
- Database: Firebase Realtime Database for efficient data storage and retrieval.
- Authentication: Firebase Authentication with support for OAuth providers.
2. User Interface:
- Home Page: Displays the food and dishes.
-	Header: Website Logo, main menu, user profile, orders, register / login / logout
-	Footer: Contact us, follow us, quick links, copyright
-	Thumbnails: Display dishes image and information with Masonry Layouts
- Food Page: Shows dishes detail and information.
- Cart Page: Shopping cart for ordered items list, add / remove, total numbers and check out
- Admin panel: Display data tables, visualization graph, restaurant settings.
3. Security:
- Firebase Authentication: Manages user authentication securely to handle secure login and registration processes.
- Secure payment gateways to handle transactions, ensuring PCI-DSS compliance.


## Links
- website: [www.imenu.ca](https://www.imenu.ca 'Intelligent Menu and Order System')
