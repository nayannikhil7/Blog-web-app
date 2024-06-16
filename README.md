
This repository contains the code for a fully functional blog website built using Node.js, Express.js, MongoDB, and EJS. The application features user authentication and authorization, login functionality, and a comment system, providing a seamless and secure blogging experience.

Features
1. User Authentication and Authorization
User Registration: New users can create an account by providing a username, email, and password.
User Login: Registered users can log in to access their account and interact with the blog.
Password Hashing: Passwords are securely hashed using bcrypt before storing in the database.
Session Management: User sessions are managed using Express-session, ensuring a persistent login state.
Role-based Access Control: Different levels of access are provided to users (e.g., admin and regular users) for enhanced security and functionality.

3. Blog Post Management
   
Create Post: Authenticated users can create new blog posts, adding titles, content, and images.


4. Comment Functionality
   
Add Comment: Authenticated users can comment on blog posts to engage in discussions or provide feedback.

5. User Profile Management
   
View Profile: Users can view their profile details, including the list of their blog posts and comments.


6. Responsive Design
   
EJS Templates: The website uses EJS (Embedded JavaScript) for dynamic HTML rendering, ensuring a responsive and user-friendly interface.

Bootstrap: Integrated with Bootstrap for a modern and responsive design.
