# ✍️ Notes
1. What does the term "props" stand for?
- Properties

2. What are props in React?
- They are arguments passed into React Components.

3. What are props typically used for in React?
- Usually used to pass data from one component down to another. 

4. How are props passed to components?
- Props are passed to components Via HTML attributes. 
you must use this.props.propertyname
5. What syntax is used to pass props to a component?
- Props use the same syntax as HTML attributes. 

6. A component will receive props as what kind of data type?
- A component will receive props as an Object. 

7. In order to access the data inside of props, what kind of notation should we use?
- We use dot.notation. 

8. If we are trying to send a variable in props to a component, what syntax does the variable need to be wrapped in?
- It must be wrapped in curly brackets. 

9. Can you send a custom method in props to another component?
- Yes you can. 

10. Where is the most popular place we are going to get values from to send in props to other components?
-  inside the state object.

11. When accessing a value in props, what syntax do we use?
- this.props.propertyname

12. Can you send props back up to a parent component?
- No
You gave to perform a lift state. 

13. How do you lift state?
- You can lift state by calling a function in a child component that is being defined in a parent component and passing it in a new value for the state property you are trying to update/lift up so that the application can re-render and pass the new values back down in props. 


# Resources
- [w3 Schools on React Props](https://www.w3schools.com/react/react_props.asp)
- [React Docs on Props](https://reactjs.org/docs/components-and-props.html)
- [React Docs on Lifting State](https://reactjs.org/docs/lifting-state-up.html)