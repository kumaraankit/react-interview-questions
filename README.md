# react-interview-questions


1. What is react.

    React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called      “components”.
    
2. What do you mean by declarative in react.

    React makes it painless to create interactive UIs. Design simple views for each state in your application, and React will efficiently update and render just the right             components when your data changes. Declarative views make your code more predictable, simpler to understand, and easier to debug.
    
3. What is the difference between imperative and declarative.

    The word "imperative" here implies "commanding" the computer to do something. We have to directly tell the browser exactly how to do every little thing we need it to do. This     is "the old way", and it's what you do with vanilla JavaScript or something like jQuery.


3. Explain the architecture of react and what does unidirectional data flow means in react.

    Flux is a new kind of architecture that Facebook uses when it works with React.
    The core principles of React are (1) Flexibility, (2) Efficiency and (3) Declarative code
    Flux is open source and more of a design pattern than a formal framework and you can use it immediately. What keeps it apart from other frameworks is that it is different       from the MVC Design pattern.

    Flux keeps code predictable when compared to other MVC frameworks.
    Flux boasts of a better-structured data flow – unidirectional. Being unidirectional is the central feature of Flux. The actions are propagated to the new system with regard    to user interactions. 
    In a typical Flux architecture, you will find the following components:

    **Actions** - Helpers that pass data to the Dispatcher.

    **Dispatcher** - Receives these Actions and broadcasts payloads to registered callbacks.

    **Stores** - Act as containers for application state and logic. The real work in the application is done in the Stores. The Stores are registered to listen in on the actions       of the Dispatcher and update the Views according to these actions.

    **Controller** **Views** - React Components grab the state from the stores and then pass it down to the child components.

    When an event happens, the Dispatcher would send the “payload” to the Store that is registered to listen for that particular action. Now it is up to the Store to update the     View, which in turn triggers an action. The action to that will occur is also predetermined, like name, the type of action, and so on.

    The View propagates the Action through a central Dispatcher and this will be sent to various Stores. These Stores contain an application’s business logic and other data.

    This proves that the Flux pattern follows a unidirectional data flow. The Action, Dispatcher, Store, and View are independent nodes with specific inputs and outputs. The         data flows through the Dispatcher, the central hub, which in turn manages all the data. The Dispatcher acts as a registry with registered callbacks that the Stores respond       to. Stores will emit a change which will be picked by the Controller-Views.

    Refer for more details- 
    https://dzone.com/articles/a-detailed-study-of-flux-the-reactjs-application-a#:~:text=React%20%2D%20a%20popular%20front%2Dend,function%20hooks%20to%20render%20HTML.


5. What are the features of react.

    The different features of react are:
    
     **Virtual DOM
     One way data binding
     declarative code
     component based architecture
     Flexible
     Efficient
     JSX**
7. What is the difference between react, angular and vue js.
8. What does create-react-app do.
9. Explain the folder structure of react app.
10. What are components in react.

    Components are a part of user interface, one screen can be divided into several components e.g sidebar, header, footer, navbar , content.
    Components are reusable in nature and also can be nested into other components.
12. Explain state.

    State is a plain JavaScript object used by React to represent an information about the component's current situation. It's managed in the component (just like any variable       declared in a function).

    the State of a component is an object that holds some information that may change over the lifetime of the component
14. Why do we need state.

    State allows us to manage changing data in an application. It's defined as an object where we define key-value pairs specifying various data we want to track in the             application.
    
16. What is props and its importance.

    React allows us to pass information to a Component using something called props (stands for properties). Props are basically kind of global variable or object.
    
18. What is class based component.
19. Explain JSX and also the difference between JSX and normal html.
20. What are the different rules for JSX.
21. How exactly the react works.
22. Explain functional component.
23. What are the different ways through which destructuring of state and props is possible.
24. Explain event handling in react with respect to class based and functional component.
25. Why we prefer functional component over class based.
26. Explain the difference between class based and functional based component.
27. Why do we need to bind event handlers and in how many ways we can do it.
28. How can we pass methods as props.
29. How do we conditionally render react.
30. Explain the usage of list rendering and use of map in react.
31. Explain list as keys.
32. How do we handle forms in react.
33. Explain controlled or uncontrolled forms.
34. Explain component life cycle methods and different phases.
35. What are fragments and its different ways and also importance.
36. What are pure components and its importance.
37. Explain memo.
38. Explain refs and its importance with applications.
39. What is the use of forwarding refs.
40. Why do we need portals.
41. How do we handle react errors i.e error boundary.
42. Explain HOC with small example.
43. What are render props and its importance.
44. Explain the importance of context.
45. What is prop drilling.
46. How do we handle the http request in react.
47. What are reconcilliation.
48. What are hooks and its associated rules.
49. Why do we need hooks.
50. Explain the use of useState and its syntax.
51. Explain useState with array.
52. Explain useState with objects.
53. How useState works with the previous state.
54. What are useEffect.
55. Explain the working of useEffect.
56. How can we run effects conditionally.
57. Explain useEffects with cleanup.
58. Explain useEffect with incorrect dependency.
59. Explain data fetching in effects.
60. Explain context hook and its importance.
61. Why do we need useReducer.
62. How to use multiple useReducers.
63. Explain the data fetching in useReducer.
64. What is the difference between useState and useReducer.
65. Explain useCallback hook.
66. Explain useMemo hook.
67. Explain useRef hook.
68. What are custom hooks and how can we implement them.
69. Explain state immutability.
70. How to optimize react.
71. Explain the working of virtual dom and also figure out the differences from real dom.
72. Why do we prefer virtual DOM.
73. What are function creators.
74.Explain action , types and reducer.
75. Explain useHistory.
76. Explain useLocation.


REDUX

1. What is redux and its importance.
2. Explain the three principles of redux.
3. Explain actions, reducers and store.
4. What are middleware in react and its use nd why do we need them.
5. Explain redux thunk.
6. Explain connect in redux.
7. How to setup redux in react.
8. Explain react-redux with hooks.
9. Explain the working of useSelector and useDispatch.
10. What is the importance of action payload.
11. Explain the rules associated with reducers.
12. Why do we need global state.
13. Explain mapStateToProps.
14. Explain mapDispatchtoProps.
15. What are pure components and how does it affect or help reducers.
16. Explain the architecture of redux.
17. What are action creator.
18. Explain the react-redux providerworks.
19. How can we keep our reducers pure.



