# Simple Shopping Website

Welcome to the Simple Shopping Website project repository! This project aims to provide you with hands-on experience in developing a network application based on the client/server architecture. The objective is to build a web application for a simple shopping website where users can browse products, add items to their cart, register/login, and perform other essential functions.

## Components

### Users Login (Main Page)
- Registered users can log in using their stored username and password.
- If an unregistered user tries to log in, an error message will be displayed.

### User Registration
- Users can create an account using a unique username and password.
- User information is stored in a MongoDB database.
- Error message displayed if the username is already taken.

### Home Page
- The home page displays item types and a button to view the user's cart.
- Clicking on an item type redirects the user to that type's page.

### Type Page
- Shows all items within a specific type.
- Clicking on an item's name redirects the user to that item's page.

### Item Page
- Contains a description of the item.
- Includes an embedded link for a video describing the item (video not included in the folder).
- "Add to Cart" button adds the item to the user's cart in the database.

### Cart Page
- Displays items previously added to the user's cart.
- Includes a "View Cart" button on the home page to access the user's cart.

### Search
- Search bar available on all pages (except registration and login).
- Searches items by name only.
- Results display either "item not found" or a list of items containing the search keyword.
- Clicking on search results directs the user to the specific item's page.


## Technologies

- **Node.js**
- **Express**
- **MongoDB**
- **Embedded JavaScript (EJS)**: EJS is the template engine used to generate HTML with plain JavaScript.

## Conclusion

This project provides you with a practical opportunity to develop a web application using various technologies and deploy it on a cloud platform. By following the guidelines and utilizing the specified technologies, you will gain valuable experience in building network applications based on the client/server architecture.

Thank you for your interest in the Simple Shopping Website project. For any inquiries or assistance, please reach out to the project maintainers. Happy coding! 🛒💻
