# GamesPlay

Welcome to GamesPlay

# Overview
 The app allows visitors to browse different types of games, including the latest collections, with different levels of difficulty. Users can register with an email and password, which allows them to create their own games. Game authors can also edit or delete their own posts at any time.
 A Single Page Application (SPA) is a web application or website that interacts with the user by dynamically rewriting the current page rather than loading entire new pages from the server. This approach avoids interruption of the user experience between successive pages, making the application behave more like a desktop application.

 # How It Works

 A SPA loads a single HTML page and dynamically updates the content as the user interacts with the app.
When a user first visits the SPA, the server sends only the initial HTML, CSS, and JavaScript files necessary to load the application. Unlike traditional multi-page applications, the entire webpage is not reloaded during user interaction.



<h1>Local installation</h1>

<>h2To install and preview locally, follow these steps:</h2>

1. **Clone the repository to your local machine:**
2. **Navigate to the File Explorer and Open in Termin (writing cmd in the File Explorer path and pressing Enter)**
3. **To initialize the project, we have to execute the following commands via the command-line terminal:**
4. **npm install- command for install all packages and dependencies.**
5.  **npm run server- used to start a server or back-end process.**
6.  **npm run start- used to start a script defined under the "start" key in your package.json file.**

# Application overview

<h2>Home Page</h2>

All users should be greeted from the homepage, where they should be able to see the three most recently added games. Clicking on the details links leads to the details page for the selected game. 

    
![HomePage](https://github.com/user-attachments/assets/d06fdf12-b6a4-4df5-a7b4-43307032deed)

![HomePage2](https://github.com/user-attachments/assets/f8d3dd73-8f30-4175-b265-c50ff1f719cf)

If no games have been added yet, show the text "No games yet" instead.

![NoGameYet](https://github.com/user-attachments/assets/da002063-ab6a-4160-bb96-f63a1ba223ce)

<h2>Navigation Bar</h2>

Navigation links should correctly change the current page (view). GamesPlay link should redirect to the Home page. Guests (un-authenticated visitors) can see the links to the All Games (Catalogue) page, as well as the links to the Login and Register pages. The logged-in user navbar should contain the links to All Games (Catalogue) page, the Create page and a link for the Logout action.

Guest navigation example: 

![GussNav](https://github.com/user-attachments/assets/e93d7c20-bde8-4b37-91db-2b2aa7206860)

User navigation example: 

 ![userNav](https://github.com/user-attachments/assets/8bd70891-3adb-4da6-88d0-975e211ef938)

 <h2>Login User</h2>

 The Login page contains a form for existing user authentication. By providing an email and password, the app should login a user in the system if there are no empty fields.

 ![loginUser](https://github.com/user-attachments/assets/a2c5e3a0-fc16-4b93-87e0-4e7cdfde349c)

 <h2>Register User</h2>

![registerUser](https://github.com/user-attachments/assets/cd6a334f-5ea4-4090-946d-2d651b174919)


 

