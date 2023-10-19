# Node-JS
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


