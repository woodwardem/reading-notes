# ✍️ Notes
1. What does the import statement do?
  - The import statement is used to import read only bindings that are live, which are exported by another module.

2. How does React know you are referring to a React component?
  - React knows you are referring to another React component when you use extends React.Component. 

3. What is `<Header />`, `<Main />` and `<Footer />`?
  - These are HTML elements that are imported in by JS. This is called JSX when in a JS file. 

4. Why must a user-defined component be capitalized?
  - A userdefined component must be capitalized because the capital indicates that the JSX tag is referring to a react component. 

5. What is a fragment?
 - A fragment is is top element that lets you group a list of children without adding extra nodes to the DOM. 

6. What does the keyword `class` tell us about this App Component?
  - They keyword class tells us there is a class being created, that will hold data. 

7. What does the keyword `extends` do?
  - The keyword extends is used to create a class that is the child of another class. It also can create a subclass custom class. 

8. What data type is React.Component?
  - React.Component is a class. 

9. When do you not need to implement a constructor method?
  - You do not need to implement a constructor method if you don't initialize state. 

10. What does `super(props)` do?
  - Super(props) activates the constructor method. The super keyword, activates the parent properties. Super is used to access and call functions on an objects parent. 

11. What do we know about the state object?
  - The state object contains properties inside of it. Usually, the properties inside of state start with null values. However, the properties do not belong to state they belong to the class component. 
  - When the state changes, the component will re-render. 

12. What does `render()` do?
  - Render() examines the props and the state, it then can return React elements back onto the screen. 

13. What does `export default` do?
  - Export default is used when making JS modules to export bindings to objects, functions, or values from the module so that they can be used by other programs. 

---

## 📚 Resources 
- [MDN Web Docs on import](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)
- [React Docs on User-Defined Components](https://reactjs.org/docs/jsx-in-depth.html)
- [React Docs on Fragments](https://reactjs.org/docs/fragments.html)
- [w3 Schools on Class Components](https://www.w3schools.com/react/react_class.asp)
- [MDN Web Docs on extends](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes/extends)
- [React Docs on the constructor method](https://reactjs.org/docs/react-component.html#constructor)
- [MDN Docs on super](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/super)
- [React Docs on state](https://reactjs.org/docs/state-and-lifecycle.html)
- [React Docs on render()](https://reactjs.org/docs/react-component.html#render)
- [MDN Docs on export](https://developer.mozilla.org/en-US/docs/web/javascript/reference/statements/export)
