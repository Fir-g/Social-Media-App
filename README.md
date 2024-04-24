
Social Media App
This is a full-stack social media application built using React.js, TypeScript, Tailwind CSS, and powered by Appwrite as a Backend as a Service (BaaS) solution. It allows users to create posts, explore content, like and save posts, and interact with other users through profiles and posts.

Features
Authentication System: A robust authentication system ensuring security and user privacy.
Explore Page: Homepage for users to explore posts, with a featured section for top creators.
Like and Save Functionality: Enable users to like and save posts, with dedicated pages for managing liked and saved content.
Detailed Post Page: A detailed post page displaying content and related posts for an immersive user experience.
Profile Page: A user profile page showcasing liked posts and providing options to edit the profile.
Browse Other Users: Allow users to browse and explore other users' profiles and posts.
Create Post Page: Implement a user-friendly create post page with effortless file management, storage, and drag-drop feature.
Edit Post Functionality: Provide users with the ability to edit the content of their posts at any time.
Responsive UI with Bottom Bar: A responsive UI with a bottom bar, enhancing the mobile app feel for seamless navigation.
React Query Integration: Incorporate the React Query (Tanstack Query) data fetching library for auto-caching to enhance performance, parallel queries for efficient data retrieval, and first-class mutations.
Backend as a Service (BaaS) - Appwrite: Utilize Appwrite as a Backend as a Service solution for streamlined backend development, offering features like authentication, database, file storage, and more.
Quick Start
Follow these steps to set up the project locally on your machine.

Prerequisites
Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository
bash
Copy code
git clone https://github.com/adrianhajdin/social_media_app.git
cd social_media_app
Installation
Install the project dependencies using npm:

bash
Copy code
npm install
Set Up Environment Variables
Create a new file named .env in the root of your project and add the following content:

plaintext
Copy code
VITE_APPWRITE_URL=
VITE_APPWRITE_PROJECT_ID=
VITE_APPWRITE_DATABASE_ID=
VITE_APPWRITE_STORAGE_ID=
VITE_APPWRITE_USER_COLLECTION_ID=
VITE_APPWRITE_POST_COLLECTION_ID=
VITE_APPWRITE_SAVES_COLLECTION_ID=
Make sure to fill in the environment variables with the appropriate values provided by your Appwrite setup.

License
This project is licensed under the MIT License.

Contributing
Contributions are welcome! Please feel free to open a pull request or submit an issue with any improvements or features you'd like to add.




