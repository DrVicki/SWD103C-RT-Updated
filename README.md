# SWD103C-RT: Lesson 1 Page 5

## Set Up a React18 Development Environment 

The first step in setting up your development environment is choosing your code editor. 

- Almost alk editors have essential features like autocompletion, syntax highlighting, formatting code, and smart refactoring. 
- Using them helps you prevent potential mistakes. 

We will use the Developer Tools of web browsers while debugging JavaScript code. 

- When finished setting up the development environment, your coding will be amazingly easy and fast. 

There are several tools you might consider so you could always choose any of them. No matter what tools you choose, you’ll follow a similar process to learn the lessons.

## Install NodeJS 

Go to this website https://nodejs.org/en/download and download the latest LTS version of NodeJS; then install it onto your computer.

## Install a Code Editor 

In these lessons, we’ll use Visual Studio Code (shortened to VS Code) as the code editor. 

- You can download this free at https://code.visualstudio.com/download 

### Install Essential Extensions 

VS Code supports adding extensions which help us code faster and easier. 

After installing the editor, let’s add these essential extensions: 

- Prettier - Code formatter: Enforces a consistent style by parsing your code and re-printing it with its own rules that take the maximum line length into account, wrapping code when necessary. 

- Path Intellisense: Visual Studio Code plugin that autocompletes filenames and paths.     

- Auto Rename Tag: Auto rename paired HTML/XML tags. 

- Reactjs code snippets: Code snippets for ReactJS development. 

- ES7+ React/Redux/React-Native snippets: Extensions for React, React-Native and Redux in JS/TS with ES7+ syntax. 

- ESLint: Finds and fixes problems in your JavaScript code.     

- Rainbow Brackets: Provides rainbow colors for the round brackets, the square brackets and the squiggly brackets.     

- vscode-icons: File and folder icons for Visual Studio Code.


This is a screenshot of the above extensions for your reference when searching them.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-1.png)

To install the extensions, just 

- click on the Extensions icon (as the below picture); 
- then type a name into the Search Box; 
- select the extension that you want and click its Install button.
![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-2.png)

### Install Live Server 

Live Server helps us launch a local development server with a live reload feature for static or dynamic web pages. 

To install the extension, 

- just click on the Extensions icon; 
- then type “Live Server” into the Search Box; 
- select the extension in the below picture and click its Install button. 

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-3.png)

How to run an HTML file with the Live Server?     

- Step 1: open your HTML file with the Visual Studio Code 
- Step 2: right-click on the editing area and select “Open with Live Server” or just click the button “Go Live” at the bottom-right conner of the VS Code 
- After doing the above steps, your HTML file will be loaded into a live server and available at this address:
- http://127.0.0.1:5500/

### Setting Default Formatter 

We should configure the Default Formatter to use the “Prettier - Code formatter” extension. Please follow these steps to turn it on:     

- Go to the menu and select: File > Preferences > Settings ●
- Type “default format” into the Search Box    
-  Then select the “Prettier - Code formatter” option as the below picture.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-4.png)

### Enable Formatting Code on Save 

We should enable the “Format on Save” feature to have best readable code. Please follow these steps to turn it on:   

- Go to the menu and select: File > Preferences > Settings     
- Type “format on save” into the Search Box     
- Then check the checkbox of “Editor: Format On Save” as the below picture.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-5.png)

### Disable Compact Folders 

VS Code renders folders in its explorer in a compact form. In such a form, single child folders will be compressed in a combined tree element. 

It’s only useful for Java package structures. Therefore, we should disable “Compact Folders” feature by following these steps: 

- Go to the menu and select: File > Preferences > Settings     
- Type “compact folders” into the Search Box 
- Then uncheck the checkbox of “Explorer: Compact Folders” as the below picture.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-6.png)

### Enable Word Wrap 

To get rid of the horizontal scroll bar, we could turn on the “Word Wrap” feature by following these steps:     

- Go to the menu and select: File > Preferences > Settings     
- Type “word wrap” into the Search Box     
- Then select option “on” of “Editor: Word Wrap” as the below picture.
![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-7.png)


## Using a Web Browser 

We will use Google Chrome as a tool to run and debug our React app since it is the most popular browser. 

-It also includes amazing Developer Tools that will be described below. 

### Using Developer Tools of The Browser 

The Developer Tools are usually presented as a tabbed group of panes at the right or bottom of the web browser window. 

To open the developer tools in Google Chrome, 

- Open the Chrome Menu in the upper-right-hand corner of the browser window and select More Tools > Developer tools. You can also use Shift + CTRL + J (on Windows/Linux), or Option + ⌘ + J (on macOS) to open the tools.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-8.png)

The Developer Tools will either open up in a new window or within the Chrome window as below picture.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-9.png)

We can undock it into a separate window or only change the dock side following these steps: ● 

- Click the “Customize and control Dev Tools” button in the upper-right-hand corner.    
- Then select the dock side that you want as in the below picture.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-10.png)


### Using Console Tool 

If the Console tool wasn’t selected, you might have to select the Console tab. We can check the values of variables or try JavaScript code directly in the Console tool as below. 

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-11.png)

The Console panel is the one that shows the messages you output with console.log() and any unhandled errors.

### Strict Mode of React 

The Strict Mode of React version 18 will double rendering so it can catch errors that might occur. 

- As a result, our debugging logs will be duplicated and this causes confusion to developers. - But don’t worry! Strict mode checks are run in development mode only; they do not impact the production build. 

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-12.png)

To bypass this confusing behavior, we install an extension called “React Developer Tools”.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-13.png)

After installing the extension, we can see the grayed-out characters that came from the React Strict Mode.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-14.png)


## React Set Up

Now that you have a general idea of what React is and how it works, the next step is to install a starter project provided for you. You will be working in this project throughout the next several lessons, so it is important to not skip this page.

For this course, create a folder in your SoftwareDevelopment folder named ```FEFReact```. Please add all projects to this folder to help keep yourself organized. You will be creating projects to practice the code from the lesson and projects for your Hands-On solutions. As you move through this course, you will be asked to create projects with specific names, so please add these projects into the ```FEFReact``` folder. 

To create this folder, follow the steps below:

 1. Open up your command prompt/terminal.
 2. Run the following to navigate to your Desktop
 ```
 cd Desktop
 ```
 3. Next, navigate to the ```SoftwareDevelopment``` directory in your terminal.
```
cd SoftwareDevelopment
```

You created this folder in your Front-End Foundations course. If you do not have this folder follow the directions below:

 1. Create a root folder on your desktop and name it ```SoftwareDevelopment```.
 ```
 mkdir SoftwareDevelopment
 ```
 2. Next, navigate to the ```SoftwareDevelopment``` directory in your terminal.
```
 cd SoftwareDevelopment
 ```
 3. Create a new folder within your ```SoftwareDevelopment``` folder and name it ```FEFReact```. (This folder will hold all your coursework for this course)
```
 mkdir FEFReact
 ```
 4. Then, navigate to the ```FEFReact``` directory in your terminal.
```
 cd FEFReact
 ```

Great! Now you have a folder to house all of the projects for this course. Remember to create projects when asked and make sure they live in this folder!

## Rendering with React

A React Element is the smallest building block in React. The virtual DOM is a tree structure comprised of a ```root``` element that contains other elements. This tree of virtual DOM elements is immutable, meaning it can't be changed after creation. This allows React to keep previous versions of the virtual DOM to compare against when updates are made to help ensure only the minimal amount of work is performed.

### Project Structure

Open up the ```ReactL01``` project you previously downloaded. You will be following along in this lesson and adding code to this project. Under the ```public``` folder, you should see an ```index.html``` file. After opening the file, you should see the following:

```index.html``` file:

```
<!doctype html>
<html>
    <head>
        <title></title>
    </head>
    <body>
        <div id="root"></div>
        <script src="bundle.js"></script>
    </body>
</html>
```
Above, you have a basic HTML page structure. Inside the ```<body>``` tag, there is a ```<div>``` tag with an ```id``` of ```root```. You will be working with this ```<div>``` tag shortly. Also within the ```<body>``` tag, there is a ```script``` tag. This project has already been configured to use webpack to bundle all your project's files and dependencies into a single ```bundle.js``` file. The script tag points to the ```bundle.js``` file. When you run ```npm start``` from the project directory, the webpack process is started, and it monitors any changes to your files and rebuilds the ```bundle.js``` file for you. This means you can add many JavaScript files to your ```src``` directory and they will all be available in your final page. However, you won't be directly working in the ```bundle.js``` file but in the ```index.js``` file within the ```src``` folder in your project.

Next, open up the ```index.js``` file located within the ```src``` folder. As you can see, there is an ```alert``` in that file along with nothing else. This is there to show that the project is up and running. Go ahead and remove that line of code so the ```index.js``` file is now empty.

To start using React, you need to make sure it has been imported into the ```index.js``` file, which is the file you will be writing within. This is an essential piece of React because without importing it, it will not work.

Go ahead and add the following to the ```index.js``` file.

```src/index.js``` file:
```
import React from 'react';
```
Great! Now your JS file is now ready for some React!

## Rendering with React - Continued

## Rendering an Element into the DOM

Let’s say there is a ```<div>``` somewhere in your HTML file:
```
<div id="root"></div>
```
We call this a “```root```” DOM node because everything inside it will be managed by React DOM.

Applications built with just React usually have a single root DOM node. If you are integrating React into an existing app, you may have as many isolated root DOM nodes as you like.

To render a React element, first pass the DOM element to ```ReactDOM.createRoot()```, then pass the React element to ```root.render()```:


```
const root = ReactDOM.createRoot(
  document.getElementById('root')
);
const element = <h1>Hello, world</h1>;
root.render(element);
```

### Create Element

The ```React.createElement()``` method is very useful because it creates new elements for you on the page rather than having to add the elements into your ```index.html``` file.

Below, the ```React.createElement()``` method takes in three parameters: type, props, and children.

 - **type**: the type of the HTML element (```h1```,```p```,```button```).
 - **props**: properties of the ```object({style:{size:10px}}``` or ```Eventhandlers```, ```classNames```,etc).
 - **children**: anything to be displayed on the screen.

```
import React from 'react';

React.createElement('h1', {}, 'Hello World!');
```

In the above ```createElement()``` method, the type is the HTML tag you want to create, in this case, an ```h1``` tag. Props (stands for properties) are objects that get added to the element. They can be used to add ```class``` and ```id``` names or other attributes to the element created. Later on in this module, props will serve a larger purpose. For the current example, this object is empty to visualize creating a basic element. Later on, you will see it being used. Children are zero or more elements nested inside the element. In this case, you are providing some plain text as a child of the ```h1``` tag.

Great! If you add the new ```createElement()``` method to your code, nothing will happen. That is because you are missing a piece to make this code work.

### ReactDOM (React v.18)

Install React 18 and React DOM from npm or yarn, like this:
```
npm install react react-dom
```

Then, you'll want to use ```createRoot``` instead of ```render```.

Here's what it would look like in **React 17**:

```index.js``` file:

```
import ReactDOM from 'react-dom';
import App from 'App';

const container = document.getElementById('app');

ReactDOM.render(<App />, container);
```

And here's what it looks like in **React 18**:

```index.js``` file:

```
import React from 'react;
import ReactDOM from 'react-dom';
import App from 'App';
import { createRoot } from 'react-dom/client';

const container = document.getElementById('app');

// create a root
const root = ReactDOM.createRoot(container);

//render app to root
root.render(<App tab="home" />)
```

In your ```index.js```, update ```ReactDOM.render``` to ```ReactDOM.createRoot``` to create a root, and render your app using root.



```createElement``` builds a virtual DOM element, but to get React to update the page based on it, you must use the ```createRoot``` function from the ```react-dom``` package. To start, you need to import the ```ReactDOM``` package as you did with React itself. Add the import statement so your code now looks like below:

```src/index.js``` file:

```
import React from 'react;
import ReactDOM from 'react-dom';
import App from 'App';
import { createRoot } from 'react-dom/client';
```

```React.createElement('h1', {}, 'Hello World!')```;

Next, you need to add the ```createRoot()``` function that is included in the ReactDOM package. ```createRoot()``` has two parameters. The first parameter is what you would like to render on the page. In this case, you want to render the ('```h1```', {}, '```Hello World```!');  you already have in your HTML code. The second parameter is where you would want to render. If you remember, there is a ```<div>``` in the HTML file with an ```id``` of ```root```. This is where you are going to render your newly created ```h1``` element by using ```document.getElementById('root')```.

Create the ```ReactDOM.createRoot()``` method and move the ```document.getElementById('root'). 
 
Your ```index.js``` should now look like below:

```src/index.js``` file:

 ```
import React from 'react'
import ReactDOM from 'react-dom';
import App from './App';

React.createElement('h1', {}, 'Hello World!');
 
const container = document.getElementById('app');

// create a root
const root = ReactDOM.createRoot(container);

//render app to root


ReactDOM.createRoot(document.getElementById('root')).render(
	<React.StrictMode>
		<App />
	</React.StrictMode>
);
```
 
 



 
 
 
Caution!

The above code tells React to find an element on the page with an id of root and replace its contents with your newly created element.

Try It!
Add the above code to your ```index.js``` file and navigate to ```localhost:8080```. The page will automatically update and you should now see "```Hello World!```".


 
