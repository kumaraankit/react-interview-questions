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
    
     Virtual DOM
     One way data binding
     declarative code
     component based architecture
     Flexible
     Efficient
     JSX
7. What is the difference between react, angular and vue js.
8. What does create-react-app do.
9. Explain the folder structure of react app.
10. What are components in react.
11. Explain state.
12. Why do we need state.
13. What is props and its importance.
14. What is class based component.
15. Explain JSX and also the difference between JSX and normal html.
16. What are the different rules for JSX.
17. How exactly the react works.
18. Explain functional component.
19. What are the different ways through which destructuring of state and props is possible.
20. Explain event handling in react with respect to class based and functional component.
21. Why we prefer functional component over class based.
22. Explain the difference between class based and functional based component.
23. Why do we need to bind event handlers and in how many ways we can do it.
24. How can we pass methods as props.
25. How do we conditionally render react.
26. Explain the usage of list rendering and use of map in react.
27. Explain list as keys.
28. How do we handle forms in react.
29. Explain controlled or uncontrolled forms.
30. Explain component life cycle methods and different phases.
31. What are fragments and its different ways and also importance.
32. What are pure components and its importance.
33. Explain memo.
34. Explain refs and its importance with applications.
35. What is the use of forwarding refs.
36. Why do we need portals.
37. How do we handle react errors i.e error boundary.
38. Explain HOC with small example.
39. What are render props and its importance.
40. Explain the importance of context.
41. What is prop drilling.
42. How do we handle the http request in react.
43. What are reconcilliation.
44. What are hooks and its associated rules.
45. Why do we need hooks.
46. Explain the use of useState and its syntax.
47. Explain useState with array.
48. Explain useState with objects.
49. How useState works with the previous state.
50. What are useEffect.
51. Explain the working of useEffect.
52. How can we run effects conditionally.
53. Explain useEffects with cleanup.
54. Explain useEffect with incorrect dependency.
55. Explain data fetching in effects.
56. Explain context hook and its importance.
57. Why do we need useReducer.
58. How to use multiple useReducers.
59. Explain the data fetching in useReducer.
60. What is the difference between useState and useReducer.
61. Explain useCallback hook.
62. Explain useMemo hook.
63. Explain useRef hook.
64. What are custom hooks and how can we implement them.
65. Explain state immutability.
66. How to optimize react.
67. Explain the working of virtual dom and also figure out the differences from real dom.
68. Why do we prefer virtual DOM.
69. What are function creators.
70.Explain action , types and reducer.
71. Explain useHistory.
72. Explain useLocation.


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



