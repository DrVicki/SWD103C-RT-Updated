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

IMAGE1

To install the extensions, just 

- click on the Extensions icon (as the below picture); 
- then type a name into the Search Box; 
- select the extension that you want and click its Install button.

UMAGE 2

### 1.2.2 Install Live Server 

Live Server helps us launch a local development server with a live reload feature for static or dynamic web pages. 

To install the extension, 

- just click on the Extensions icon; 
- then type “Live Server” into the Search Box; 
- select the extension in the below picture and click its Install button. 

IMAGE3

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

IMAGE 4

### 1.2.4   Enable Formatting Code on Save 

We should enable the “Format on Save” feature to have best readable code. Please follow these steps to turn it on:     

- Go to the menu and select: File > Preferences > Settings     
- Type “format on save” into the Search Box     
- Then check the checkbox of “Editor: Format On Save” as the below picture.

IMAGE 5

### 1.2.5 Disable Compact Folders 

VS Code renders folders in its explorer in a compact form. In such a form, single child folders will be compressed in a combined tree element. 

It’s only useful for Java package structures. Therefore, we should disable “Compact Folders” feature by following these steps: 

- Go to the menu and select: File > Preferences > Settings     
- Type “compact folders” into the Search Box 
- Then uncheck the checkbox of “Explorer: Compact Folders” as the below picture.

IMAFE 6

### 1.2.7 Enable Word Wrap 

To get rid of the horizontal scroll bar, we could turn on the “Word Wrap” feature by following these steps:     Go to the menu and select: File > Preferences > Settings ●    Type “word wrap” into the Search Box ●    Then select option “on” of “Editor: Word Wrap” as the below picture.

 
