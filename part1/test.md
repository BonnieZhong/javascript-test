## React interview questions

1. What is state and props in reactjs?
State is JavaScript object that is managed within the component 
    (similar to variables declared within a function).
Props is also JavaScript object that is passed to the component 
    (similar to function params) and is read-only.

2. What is high order component? How do you use it?
A higher-order component is a function that takes a component and returns a new component.

3. What is context? What are the benefits of it?
Context provides a way to share values like these between components 
    without having to explicitly pass a prop through every level of the tree.
The typical use case for Context in React is passing down user data or the number of current items in a checkout,
    because you don't really need to load that kind of data every time you rerender a component.

4. How to assign and change the value of state in a component?
Use this.state to assign value
Use this.setState to update value

5. Could you explain the life-cycle of a react component?
The life-cycle includes 3 phases: Mounting, Updating, and Unmounting.
Mounting means putting elements into the DOM.
Updating means a component is updated whenever there is a change in the component's
    state or props.
Unmounting means removing a component from the DOM.

6. What is fragment in react?
Fragments are a modern syntax for adding multiple elements to a React Component
    without wrapping them in an extra DOM node.

7. What is ref in react?
It is an attribute which makes it possible to store a reference to particular DOM nodes or React elements. 
It provides a way to access React DOM nodes or React elements and how to interact with it. 

8. What is container component? What is presentational component?
Container components are those React components which have access to the store. These components make API calls, do processing and contain the business logic of the app.
Presentational components are those components whose only job is to render a view according to the styling and data passed to them. Essentially, they do not contain any business logic.

9. How to pass a function to a component?
Pass the function as props.

10. What is portal?
Portal is a first-class way to render child components into a DOM node outside of the parent DOM hierarchy defined by the component tree hierarchy.

11. How to share state between parent component and child component? How to share state between sibling components?
Using props When passing data from a parent to child class component.
Wrapping both siblings in a parent component and handle the state inside the parent component.