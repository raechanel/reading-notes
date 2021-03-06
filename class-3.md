# Passing Functions as Props

## Review Based on [React Docs](https://reactjs.org/docs/lists-and-keys.html)

1. What does .map() return?

   *A new array with different elements but the same data.*
2. If I want to loop through an array and display each value in JSX, how do I do that in React?

   *Use curly braces.*
3. Each list item needs a unique ____.
   *String*
4. What is the purpose of a key?

  *To help React identify which items have changed, are added or are removed.*

## Review Based on [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. What is the spread operator?
List 4 things that the spread operator can do.

- The Spread operator is the use of `ellipsis` of three dots (...) to expand an iterable object to the list of arguments.
- The spread operator is useful for many things: Coping an array, Using math functions, Adding an item to a list, Adding to state in React and many more.

2. Give an example of using the spread operator to combine two arrays.

- Example:

- [...["ððððĪŠð"]] // Array [ "ððððĪŠð" ]

- [..."ððððððĨ°ððĪĐ!"] // Array(9) [ "ð", "ð", "ð", "ð", "ð", "ðĨ°", "ð", "ðĪĐ", "!" ]

- const hello = {hello: "ððððĪŠð"}
- const world = {world: "ððððððĨ°ððĪĐ!"}

- const helloWorld = {...hello,...world}
console.log(helloWorld) // Object { hello: "ððððĪŠð", world: "ððððððĨ°ððĪĐ!" }

3. Give an example of using the spread operator to add a new item to an array.

- const fewFruit = ['ð','ð','ð']
- const fewMoreFruit = ['ð', 'ð', ...fewFruit]
- console.log(fewMoreFruit) //  Array(5) [ "ð", "ð", "ð", "ð", "ð" ]

4. Give an example of using the spread operator to combine two objects into one

- const objectOne = {hello: "ðĪŠ"}
- const objectTwo = {world: "ðŧ"}
- const objectThree = {...objectOne, ...objectTwo, laugh: "ð"}
- console.log(objectThree) // Object { hello: "ðĪŠ", world: "ðŧ", laugh: "ð" }
- const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("ð".repeat(5))}}
- objectFour.laugh() // ððððð

## Review Based on [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. In the video, what is the first step that the developer does to pass functions between components?

  - Creates the function where the state is that's being changed.

2. In your own words, what does the increment function do?

  - Takes a variable and *increments*/ changes the value and then returns it.

3. How can you pass a method from a parent component into a child component?

  -

4. How does the child component invoke a method that was passed to it from a parent component?
  -
  
***

### Other Reading Notes

- [Introduction to React and Components](class-1.md)
- [States and Props](class-2.md)
- [Things I want to know more about](questions.md)
