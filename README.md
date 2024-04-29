# Just Another Text Editor

## Description

This application demonstrates the deployment of a Progressive Web Application. Users can take notes which will persist after the application is closed. It can also be installed onto the desktop for offline use.

## User Story

AS A developer

I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
Acceptance Criteria
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application

## Technologies

The technologies I used in this challenge includes:

Node.js
Express.js
MongoDB database
Webpack & WebpackPwaManifest Plugins
Concurrently
Babel
IndexedDB
Mini-CSS-Extract Plugin
Visual Studio Code(VS-code)
Github: Github was used to create a repository which includes all the required files, links to the projects, package.json, npmrc file, gitignore and the README file.
Gitlab: Gitlab was used to clone the project to our laptop.


## Installation


To install the challenge#19 , first create a new repository in your Github account, and then clone this repository to your local computer.
To clone: git clone https://github.com/your-username/repository-name.git   
Open the cloned repository in a visual studio code.

Open integrated terminal on server.js in order to run "npm install" on the command line to install dependencies. In addition, create a gitignore file, which should includes node_modules, .env file, and .DS_Store.

## Usage

Open the repository, run 'npm install' to install dependencies.

Open integrated terminal on server.js in order to run "npm start" to start the server.

Open the Deployed application on the browser.

Upon accessing the application, you should see the text editor interface. Optionally, when prompted, click on the "Install" button to download the web application as an icon on your desktop for quick access.

The Text Editor enables users to input, view, edit, or delete content, with instant saving facilitated by IndexedDB, ensuring secure local storage. Whether the browser is closed or the page is refreshed, the content remains retained and accessible when reopening the application.

Additionally, the Text Editor enables users to edit existing content or create new entries offline.

Below is a video demonstrating the usage of the application.


https://github.com/MohnishBhujun/PWA-J.A.T.E-19/assets/149837818/a900665b-9e96-490b-b86f-5f535d983ddc

