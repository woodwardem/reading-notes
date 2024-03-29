# ✍️ Notes

1. What does CLI stand for?
    - Command Line Interface or Command Line Interpretor or Command Line Input
    - Basically the linux terminal
    

2. What is the command line used for?
    - Used by developers and system administrators to configure computers, install software, and access features that are not available in the graphical interface.

3. What is the command that creates a new React app?
    - npx create-react-app name-my-app

4. What does create-react-app do?
    - a way to start making a react app and learning react. Lets you start building a single app application in react. Sets up an envioronemnt with the latest JS updates. 

5. What does npx stand for?
    - Node Package Extecutor

6. What does npx do?
    - NPX comes built into NPM. Its a node package runner and can execute any package from the npm registry without installing the package globally on your computer. 

7. What does npm stand for?
    - NPM stands for Node Package Manager. 

8. What does npm do?
    - It is a command line tool that aids you in installing packages both globally and locally; and mananges their versions and dependencies. 

9. What are the differences between npm and npx?
    - The npm is a manager that installs when npx is a package runner that executes. 

10. What is the command that starts the React server?
    - npm start

11. What URL do I navigate to in order to view my React app in the browser?
    - localhost: 3000

12. What is the purpose of a package.json?
    - The purpose of a package.json file is to hold and record metadata about the project. I defines functional attributes of a project that npm uses to install dependencies. 

13. What are node modules?
    - Node modules are a folder that is used to save all downloaded packages from your npmin your computer for the JS project that you have. 

14. What is the .gitignore?
    - .gitignore is a file that specifies intentionally untracked files that Git should ignore. Any file listed in gitignore will Not be pushed to Github. 

15. What is the purpose of the public directory?
    - contains HTML file, index.html. must be named exactly this. 

16. What is the purpose of the public/index.html?
    - It is the page template. Only files inside the public folder can be used from public/index.html. When the application starts this is the first page that is loaded. This is the only html file in the entire application since React is generally written using JSX. This file has a line of code, <div id="root"></div>. This line is very significant since all the application components are loaded into this div. 

17. What is the purpose of the src directory?
    -  Its the mind of our app. Contains all componenents, tests, css files. 

18. What is the purpose of the src/index.js?
    - It is the JS entry point and the JS file corresponding to the index.html. This is the most top level script that controls all the components under it. 

19. What is significant about this line of code?
`ReactDOM.render(<App />, document.getElementById(‘root’));`
    - it is saying that the app component has to be loaded into an html element with an id of root. This corresponds with the div element, that has the id of root, in the index.html. We call this a 'root' DOM node because everything inside it will be mananged by React Dom. Application built with just React usually have a single root Dom node. To render a React element into a root DOM node, pass both to ReactDom.render(). 

20. What is `ReactDOM`?
    - ReactDom is an API that provides DOM specific methods that can be used at the top level of a web app, to manage those DOM elements. ReactDom provides the render method and a few others. ReactDom.render() controls the contents of the container node you pass in. 

21. What is a difference between render() and ReactDOM.render()?
    - ReactDom.render renders your components to the DOM while a component's render returns the elements that make up the components. 

22. What is React.StrictMode?
    - It is a developmental tool and you don;t need to worry about it impacting your production build. It is a helper component that will help you write better react components, you can wrap a set of components with <StrictMode /> and it will: 
    -verify that the components inside are following the recommended practices and warn you if not in the console.
    - verify the deprecated methods are not being used, and if they're used strict  mode will warn you in the console. 
    -help you prevent some side effects by identifying potential risks. 

23. What can I get rid of when I am ready to start customizing my React application?
    -public/favicon.ico
public/logo192.png & logo512.png
public/manifest.json
public/robots.txt
src/App.test.js
src/logo.svg
src/setupTests.js
src/reportWebVitals.js
App.css: delete everything from line 5 and down
inside of index.js:
this text:
// If you want to start measuring performance in your app, pass a function
// to log results (for example: reportWebVitals(console.log))
// or send to an analytics endpoint. Learn more: https://bit.ly/CRA-vitals
reportWebVitals();
//got this from ms,King's git hub 
this import:
import reportWebVitals from './reportWebVitals';
inside of App.js:
this import:
import logo from './logo.svg';
this code:
<!--<header className="App-header">
    <img src={logo} className="App-logo" alt="logo" />
    <p>
      Edit <code>src/App.js</code> and save to reload.
    </p>
    <a
      className="App-link"
      href="https://reactjs.org"
      target="_blank"
      rel="noopener noreferrer"
    >
      Learn React
    </a>
  </header>!-->

24. Where can I find build instructions and other helpful React tips?
    - in the ReadMe.md that is generated from CRA. 

25. How do I close down the React server?
    - type control + C in the Terminal. 

# Resources
- [w3Schools: CLI](https://www.w3schools.com/whatis/whatis_cli.asp)
- [What Is package.json?](https://heynode.com/tutorial/what-packagejson/)
- [CRA File Structure Explained](https://medium.com/@abesingh1/create-react-app-files-folders-structure-explained-df24770f8562)
- [A quick guide to help you understand and create ReactJS apps](https://www.freecodecamp.org/news/quick-guide-to-understanding-and-creating-reactjs-apps-8457ee8f7123/)