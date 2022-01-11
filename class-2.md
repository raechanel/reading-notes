# States and Props

Review Based on [React Lifecycle](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  The `render` happens first then the `componentDidMount`
2. What is the very first thing to happen in the lifecycle of React?
  The mounting phase. A constructor is the first thing that is called.
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
  The order goes like this: `constructor, render, React Updates, componentDidMount, componentWillUnmount`
4. What does componentDidMount do?
  This method loads anything using a network request or initialize the DOM. Also, allows us to execute tHe React code when the component is already placed in the DOM.

***

## Video Review

Review based off [React State vs Props](https://www.youtube.com/watch?v=IYvD9oBCuJI)

1. What types of things can you pass in the props?
  Any data type can be passed through: strings, functions, objects, etc.
2. What is the big difference between props and state?
  Props are passed `into` a component and handled `outside` of that component. State is handled `inside` that component.
3. When do we re-render our application?
  When you change the state inside of your application.
4. What are some examples of things that we could store in state?
  Inside of a form.

## Notes

* React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

| Phase        |    Description    |
| ---------    |    ------------   |
| Render Phase | Pure and has no side effects. May be paused, aborted, or restarted by React. |
|Pre-commit phase | Can read the DOM. |
| Commit Phase | Can work with DOM, run side effects, schedule updates |

***

## Other Resources

* [React Bootstap Documentation](https://react-bootstrap.github.io/)
* [Netlify](https://www.netlify.com/)

## Other Reading Notes

* [Introduction to React and Components](class-1.md)
* [Things I want to know more about](questions.md)
