# React and Forms

## Review based on [React Docs - Forms](https://reactjs.org/docs/forms.html)

1. What is a ‘Controlled Component’?
    - An input form element whose value is controlled by React

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
    - U
3. How do we target what the user is entering if we have an event handler on an input field?
    - Add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

## Review based on [The Conditional (Ternary) operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

1. Why would we use a ternary operator?
    - To shorten if statements into one line conditional
2. Rewrite the following statement using a ternary statement:
    Original:
    - if(x===y){
      console.log(true);
      } else {
        console.log(false);
      }

    Rewrite:
    - x===y (console.log) true : false

***

### Other Reading Notes

- [Introduction to React and Components](class-1.md)
- [States and Props](class-2.md)
- [Passing Functions as Props](class-3.md)
- [Things I want to know more about](questions.md)
