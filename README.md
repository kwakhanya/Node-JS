# Node-JS Week 3
Introduction to Node JS
Node.js is an open-source, server-side JavaScript runtime environment that allows developers to build and run JavaScript applications outside of a web browser. It is built on the V8 JavaScript engine, which is developed by Google and used in the Chrome web browser. Node.js enables developers to write server-side code in JavaScript, making it possible to use the same programming language for both the front-end and back-end of web applications.
How to install NodeJS and NPM for Windows
 The first steps in using Node.js is the installation of the Node.js libraries on the client system. To perform the installation of Node.js, perform the below steps;

Go to the site https://nodejs.org/en/download/ and download the necessary binary files. In our example, we are going to the download the 32-bit setup files for Node.js.
Double click on the downloaded .msi file to start the installation. Click the Run button in the first screen to begin the installation.
The other way to install Node.js on any client machine is to use a "package manager".

In windows, the node package manager is known as Chocolatey. It was designed to be a decentralized framework for quickly installing applications and tools that you need.

To install Node.js via Chocolatey, the following steps need to be performed.

The Chocolatey website (https://chocolatey.org/) has very clear instructions on how this framework needs to be installed.

The first step is to run the below command in the command prompt windows. This command is taken from the Chocolatey web site and is the standard command for installing Node.js via Chocolatey. The below command is a PowerShell command which calls the remote PowerShell script on the Chocolatey website. This command needs to be run in a PowerShell command window. This PowerShell script does all the necessary work of downloading the required components and installing them accordingly.
 What is Node JS?
Node.js is an open-source, server-side JavaScript runtime environment that allows developers to build and run JavaScript applications outside of a web browser. It is built on the V8 JavaScript engine, which is developed by Google and used in the Chrome web browser.
How is Node JS initiated on a computer?
You have to download it first, then install it in your computer.


Why do we use Node JS?
Node JS is asynchronous

What can Node JS do?
Node.js can create, open, read, write, delete, and close files on the server

What is a module in Node JS the same as in JavaScript?
It is a function that you want to include in your application,libraries.

What is NPM?
Node Package Manager
In windows, the node package manager is known as Chocolatey. It was designed to be a decentralized framework for quickly installing applications and tools that you need.

What is contained in a Node JS Package?
A package in Node.js contains all the files you need for a module.

Client side game development
Node.js itself is often used on the server side, so game development in Node.js typically involves using a combination of Node.js for server-side logic and web-based technologies (HTML5, CSS, and JavaScript) for the client-side rendering and interaction with sprites. Libraries and frameworks that provide support for 2D graphics and sprites, such as Phaser and PixiJS, are commonly used with Node.js for game development. These libraries simplify the process of working with sprites, animations, and other game-related elements in web-based games.
Sprites
 Sprite typically refer to a concept used in 2D graphics and game development. Sprites are graphic images or objects that can be moved, manipulated, and displayed on a 2D canvas or screen. They are a fundamental building block for creating 2D games, animations, and interactive applications. Sprites can represent characters, objects, or any visual elements in a 2D environment.
Code Snippet
 This code controls the rotation of a game object (sprite) in response to user input. When the "A" key is pressed, the object rotates counterclockwise, and when the "D" key is pressed, it rotates clockwise. When neither key is pressed, the object's angular velocity is set to 0, indicating that it should stop rotating. The rotation speed is scaled by the this.speed property divided by 1000 to control the rotation rate.
Assigning a Sprite
Assigning a sprite to a player in a game typically involves creating a visual representation of the player character using a sprite object and associating it with the player's properties and behavior.
Prepare Sprite Assets:

You need sprite assets, which are the images or animations that represent the player character. These assets can be in the form of image files (e.g., PNG or JPEG) or animated sprite sheets.
Load Sprite Assets:

Load the sprite assets using a game development library or framework. For example, if you're using a library like Phaser or PixiJS in a web-based game, you would load the player's sprite assets using their respective methods.
Create Player Sprite:

Create a player sprite object using the loaded assets. Set its initial position, scale, and other properties as needed.
Associate Player Properties:

Assign properties to the player character, such as its speed, health, or any other attributes relevant to your game. These properties can be stored in a player object or component.
Control Player Behavior:

Implement code to control the player's behavior, such as handling player input (keyboard or touch controls), responding to collisions, and updating the player's position and animations.
Rendering Player:

Ensure the player's sprite is rendered in the game scene. This typically involves adding the player sprite to the game world or scene.
Update Loop:

In the game's main update loop, update the player's position, animation, and other properties as the game progresses.

week 4
Day 1
Installing and Building App Components
React Native is an open-source framework for building mobile applications using JavaScript and React. It was developed by Facebook and was first released in 2015. React Native allows developers to create native mobile applications for iOS, Android, and other platforms using a single codebase, which is primarily written in JavaScript.
1.	Create a package.json file (if it doesn't already exist): If you don't have a package.json file in your project directory, you can create one by running the following command and following the prompts:
bashCopy code
npm init 
2.	Install a Dependency: To install a Node.js package (dependency), use the npm install command followed by the package name. For example:
bashCopy code
npm install package_name 
Replace package_name with the name of the package you want to install.
3.	Save the Dependency to package.json: By default, npm will save the installed package as a dependency in your package.json file. This means it will be listed under the "dependencies" section, and you can specify its version there. If you want to save the package as a development dependency, use the --save-dev or -D flag:
bashCopy code
npm install package_name --save-dev 
4.	Global Install (optional): If you want to install a package globally, which makes it available as a command-line tool, use the -g flag:
bashCopy code
npm install -g package_name 
However, be cautious when installing packages globally, as it can lead to version conflicts and is generally not recommended for project-specific dependencies.
5.	Check package.json for Installed Dependencies: After installing dependencies, you can check your package.json file to see the list of installed packages and their versions.
6.	Install All Dependencies from package.json: If you're working on a project with an existing package.json file, you can install all the listed dependencies by running:
bashCopy code
npm install 
This will read your package.json file and install all the dependencies listed.
7.	Remove Dependencies: To remove a dependency, you can use the npm uninstall command. For example:
bashCopy code
npm uninstall package_name 
Remember to replace "package_name" with the actual name of the Node.js package you want to install or uninstall.

Installing dependencies
 Installing dependencies typically refers to the process of adding or setting up the software and libraries that a particular program or application relies on in order to function correctly. The specific steps and commands for installing dependencies can vary depending on the programming language and the platform you are using.
Setting up the Server
 Setting up a server involves preparing a computer or virtual machine to host services, applications, or websites. The specific steps for setting up a server can vary depending on the purpose of the server (web server, database server, file server, etc.) and the operating system you are using.
 Modifying npm scripts
 Modifying NPM (Node Package Manager) scripts is a common task when working on a Node.js project. NPM scripts are defined in the package.json file of your project, and they provide a convenient way to run various tasks, such as building, testing, or starting your application.

Day 2
When working with React Native, you can use npm or yarn to install and manage dependencies for your mobile app. Here are the steps to install dependencies in a React Native project:

1. **Create a React Native Project:**
   If you haven't already created a React Native project, you can do so using the following command:
   ```bash
   npx react-native init YourAppName
   ```

   Replace `YourAppName` with the name of your project.

2. **Navigate to the Project Directory:**
   Change your working directory to the root of your React Native project.
   ```bash
   cd YourAppName
   ```

3. **Install Dependencies:**
   To install dependencies, you can use npm or yarn. Here are examples using both package managers:

   **Using npm:**
   ```bash
   npm install
   ```
   
   **Using yarn:**
   ```bash
   yarn
   ```

   Running either of these commands will read the `package.json` file in your project directory and install the required packages and libraries listed in the dependencies.

4. **Add Specific React Native Packages:**
   To add specific React Native packages or libraries, you can use `npm install` or `yarn add`. For example:
   
   **Using npm:**
   ```bash
   npm install react-navigation
   ```

   **Using yarn:**
   ```bash
   yarn add react-navigation
   ```

   Replace `react-navigation` with the name of the package you want to add.

5. **Link Native Modules (if necessary):**
   Some React Native packages may require linking of native modules. If a package's documentation suggests linking, you can do it using the following command:
   ```bash
   npx react-native link
   ```

6. **Check for Native Dependencies:**
   If you add a library with native code, make sure to follow the installation instructions provided by the library's documentation. You may need to link native modules, configure Gradle or Xcode settings, or make other platform-specific adjustments.

7. **Verify Installation:**
   After installation, you can verify that your dependencies are correctly listed in your `package.json` file, and you can also check if your app builds and runs as expected.

Keep in mind that React Native projects may also use a separate `android` and `ios` folder for platform-specific code and dependencies, so be sure to check the respective platform-specific directories if you have platform-specific dependencies.

Always consult the official documentation of the packages you're using and refer to any specific instructions or requirements mentioned there.
Building Index Page
Building an index page in a React Native project typically involves creating a component or screen that serves as the main entry point for your app. This index page can be used to display content or navigate to other parts of your application.
Pusher is a platform that provides real-time communication and event-driven functionality for web and mobile applications. It allows developers to build real-time features such as chat, notifications, live updates, and more in their applications. Pusher offers various products and libraries to facilitate real-time communication. Here's a basic overview of how to build a simple real-time chat app using Pusher:

1. **Create a Pusher Account:**
   To get started, sign up for a Pusher account at [https://pusher.com](https://pusher.com). You'll need to create a new app on the Pusher dashboard.

2. **Set Up a Backend Server:**
   You'll need a backend server to handle communication between clients and Pusher. You can use any backend technology, such as Node.js, Ruby on Rails, or Django. Your server will handle client connections and publish messages to Pusher.

3. **Install the Pusher Library:**
   Depending on your choice of backend technology, you'll need to install the appropriate Pusher library or SDK. For example, if you're using Node.js, you can use the `pusher` library:

   ```bash
   npm install pusher
   ```

4. **Configure Pusher:**
   You'll need to configure the Pusher library with your app's credentials. You can find these credentials in your Pusher dashboard.

   ```javascript
   const Pusher = require('pusher');

   const pusher = new Pusher({
     appId: 'YOUR_APP_ID',
     key: 'YOUR_APP_KEY',
     secret: 'YOUR_APP_SECRET',
     cluster: 'YOUR_APP_CLUSTER',
   });
   ```

5. **Client-Side Integration:**
   On the client side (e.g., a web or mobile app), you'll need to include the Pusher JavaScript library. You can do this using a script tag or by installing it via npm or yarn. Initialize Pusher with your app's credentials:

   ```html
   <script src="https://js.pusher.com/7.0/pusher.min.js"></script>
   ```

   ```javascript
   const pusher = new Pusher('YOUR_APP_KEY', {
     cluster: 'YOUR_APP_CLUSTER',
   });
   ```

6. **Real-Time Events:**
   Implement real-time events in your application. For a chat app, you might have events like "new_message" or "user_typing." When a user sends a message, you publish the message to Pusher, and Pusher broadcasts the message to all connected clients.

   ```javascript
   // Server-side
   pusher.trigger('chat', 'new_message', {
     text: 'Hello, world!',
     sender: 'User123',
   });
   ```

   ```javascript
   // Client-side
   const channel = pusher.subscribe('chat');
   channel.bind('new_message', function(data) {
     // Handle the new message on the client
     console.log(data.text);
   });
   ```

7. **Build the Chat UI:**
   Create the user interface for your chat application on the client side. You can use HTML, CSS, and JavaScript (or a mobile framework) to build the chat interface.

8. **Testing and Deployment:**
   Test your real-time chat application locally. When you're ready, deploy both your frontend and backend to a hosting service.

Pusher provides additional features and products, including Presence channels for user presence management and WebSockets for even lower latency. Be sure to consult the Pusher documentation and resources specific to your chosen backend and frontend technologies for more detailed information and examples.



