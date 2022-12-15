<img align="left" width="116"  src="./Assets/react-logo.png" />

# &nbsp;**Welcome to the React Incubator** [![Twitter Follow](https://img.shields.io/twitter/follow/Entelect.svg?style=social&label=Follow)](https://twitter.com/Entelect)

<br/><br/>

## **What you will be learning?**

- [ ] Resources
- [ ] Setup
- [ ] What is React?
- [ ] Basic React Tutorial
  - [ ] Learning Outcomes
  - [ ] Tip
- [ ] Advanced React Tutorial
- [ ] What is TypeScript?
- [ ] React TypeScript Tutorial
- [ ] React Unit Testing

## **Resources**

- [React Docs](https://reactjs.org/docs/getting-started.html)
- [Awesome React](https://github.com/enaqx/awesome-react)
  
## **Setup**

- [ ] [Setup](https://github.com/entelect-incubator/React/blob/master/Setup.md)

# **What is React?**

React is a library created by Meta (previously Facebook) and has gained popularity as one of the big three popular web frameworks (the others being Angular and Vue). It follows a declarative, component-based approach and doesn't make assumptions about the rest of your technology stack, furthering a learn once, write anywhere learning mindset.

## **Why should I learn about it?**

One of its most significant advantages is that it is relatively tech agnostic and allows teams to compose their applications with technology choices that make sense for the application they are building.

## **Fragments**

One of the most useful features introduced by React 16 is Fragments because React components are required to have only one root element. React 16 introduced the React.Fragment wrapper allows child component wrapping, meaning that an element can have multiple child elements at its root, with one parent element, the Fragment, which does not get rendered to the DOM. React.Fragments help alleviate the DOM nesting that React < 16 was prone to due to having to wrap the contents of an element with multiple root elements in something else, like a div.

# **Basic React Tutorial**

Facebook's React Tutorial is an excellent starting place, as it covers theoretical and practical aspects of React. Completing Facebook's React tutorial shouldn't take more than a day.

## **Learning Outcomes**

After going through the practical, you should be familiar with the following concepts:

- [ ] ES 6
- [ ] JSX
- [ ] React application State and Lifecycle
- [ ] Handling events
- [ ] React classes
- [ ] Hoisting State
- [ ] NPM / YARN

## **Intro to React**

- [ ] [Tutorial: Intro to React](https://reactjs.org/tutorial/tutorial.html)

<details>
<summary>Tip</summary>

- As a React developer, you should endeavour to modify your DOM only by modifying the state or properties of your components.

- Whenever a state change is made, React will diff its Virtual-DOM against the real DOM and fire off update requests to components affected by the state changes.

  - Pseudo events can be used to react to user interaction with the real DOM and should trigger state changes.

  - Only if it is absolutely necessary should references to the DOM be used to manipulate the DOM directly. Modifying state or properties only ensures that the changes made to the DOM by components are predictable and application logic is encapsulated.

- Calls to <component>.setState are asynchronous and batched;

  - Do not call <component>.setState, and immediately expect to be able to do something with the results of the call.

  - The [setState(updater[, callback])](https://reactjs.org/docs/react-component.html#setstate) function accepts a second parameter, a callback which can be used to do something as soon as the state changes.

- React lends itself to componentizing a website's fragments, so try to create components from code you often repeat.

  - In the same breath, try to give components as few responsibilities as possible.

- If you need to make Ajax requests, do them in the componentDidMount lifecycle method.

- Familiarise yourself with the [rich component API](https://reactjs.org/docs/react-component.html), there's probably a function that'll help you do what you want to do.

</details>


