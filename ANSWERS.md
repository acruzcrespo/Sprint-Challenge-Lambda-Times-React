- [X] What are PropTypes used for? Please describe why it's important to type check our data in JavaScript.

    -PropTypes are used to making runtime assertions about what type of data a React component requires in order to render properly, it is where you define what props your component needs and what type(s) they should be. 

- [X] Describe a life-cycle event in React?

    -The first event is the Mounting phase: this is the phase when the component is being built out from ground up. Whatever initial data you’ll have access to will be defined on the constructor of this phase, in other words is where your render method is invoked. The second phase is the Updating Phase: here setState can be used to change the component’s state data, forcing a call to render. The last one is the Un-mounting Phase: this is when the component is removed from the screen.

- [X] Explain the details of a Higher Order Component?

    -Higher Order Component (HOC) is an advanced React JS pattern that allows us the capability of reusing component logic. Also, an HOC is a function that receives a component as an argument and returns a new component source.

- [X] What are three different ways to style components in React? Explain some of the benefits of each.

    -In React, there are several ways to style the components, one of them is inline styles, they are not specified as a string. Instead they are specified with an object whose key is the camelCased version of the style name, and whose value is the style’s value, usually a string. Another concept is using CSS in JS to abstract CSS to the component level itself, using JavaScript to describe styles in a declarative and maintainable way. With the release of the popular styled-components project. The third one are styled-components, they are created by defining components using the ES6 template literal notation. CSS properties can be added to the component just like you would do using CSS.defining styled-components with encapsulated styles without CSS classes as a mediator layer.

