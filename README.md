# set-up-react-dev-environment

## Set Up a Development Environment 

The first step in setting up your development environment is choosing your code editor. 

- Almost alk editors have essential features like autocompletion, syntax highlighting, formatting code, and smart refactoring. 
- Using them helps you prevent potential mistakes. 

We will use the Developer Tools of web browsers while debugging JavaScript code. 

- When finished setting up the development environment, your coding will be amazingly easy and fast. 

There are several tools you might consider so you could always choose any of them. No matter what tools you choose, you’ll follow a similar process to learn the lessons.

## 1.1 Install NodeJS 

Go to this website https://nodejs.org/en/download and download the latest LTS version of NodeJS; then install it onto your computer.

## 1.2 Install a Code Editor 

In these lessons, we’ll use Visual Studio Code (shortened to VS Code) as the code editor. 

- You can download this free at https://code.visualstudio.com/download 

### 1.2.1 Install Essential Extensions 

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

### 1.2.2 Install Live Server 

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

### 1.2.3 Setting Default Formatter 

We should configure the Default Formatter to use the “Prettier - Code formatter” extension. Please follow these steps to turn it on:     

- Go to the menu and select: File > Preferences > Settings ●
- Type “default format” into the Search Box    
-  Then select the “Prettier - Code formatter” option as the below picture.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-4.png)

### 1.2.4   Enable Formatting Code on Save 

We should enable the “Format on Save” feature to have best readable code. Please follow these steps to turn it on:     

- Go to the menu and select: File > Preferences > Settings     
- Type “format on save” into the Search Box     
- Then check the checkbox of “Editor: Format On Save” as the below picture.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-5.png)

### 1.2.5 Disable Compact Folders 

VS Code renders folders in its explorer in a compact form. In such a form, single child folders will be compressed in a combined tree element. 

It’s only useful for Java package structures. Therefore, we should disable “Compact Folders” feature by following these steps: 

- Go to the menu and select: File > Preferences > Settings     
- Type “compact folders” into the Search Box 
- Then uncheck the checkbox of “Explorer: Compact Folders” as the below picture.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-6.png)

### 1.2.6 Enable Word Wrap 

To get rid of the horizontal scroll bar, we could turn on the “Word Wrap” feature by following these steps:     

- Go to the menu and select: File > Preferences > Settings     
- Type “word wrap” into the Search Box     
- Then select option “on” of “Editor: Word Wrap” as the below picture.
![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-7.png)


## 1.3 Using a Web Browser 

We will use Google Chrome as a tool to run and debug our React app since it is the most popular browser. 

-It also includes amazing Developer Tools that will be described below. 

### 1.3.1   Using Developer Tools of The Browser 

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


### 1.3.2 Using Console Tool 

If the Console tool wasn’t selected, you might have to select the Console tab. We can check the values of variables or try JavaScript code directly in the Console tool as below. 

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-11.png)

The Console panel is the one that shows the messages you output with console.log() and any unhandled errors.

### 1.3.3 Strict Mode of React 

The Strict Mode of React version 18 will double rendering so it can catch errors that might occur. 

- As a result, our debugging logs will be duplicated and this causes confusion to developers. - But don’t worry! Strict mode checks are run in development mode only; they do not impact the production build. 

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-12.png)

To bypass this confusing behavior, we install an extension called “React Developer Tools”.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-13.png)

After installing the extension, we can see the grayed-out characters that came from the React Strict Mode.

![](https://github.com/DrVicki/set-up-react-dev-environment/blob/main/react-dev-env-images/image-14.png)





 
