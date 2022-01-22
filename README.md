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
6. What is the difference between react, angular and vue js.
7. What does create-react-app do.
8. Explain the folder structure of react app.
9. What are components in react.
10. Explain state.
11. Why do we need state.
12. What is props and its importance.
13. What is class based component.
14. Explain JSX and also the difference between JSX and normal html.
15. What are the different rules for JSX.
16. How exactly the react works.
17. Explain functional component.
18. What are the different ways through which destructuring of state and props is possible.
19. Explain event handling in react with respect to class based and functional component.
20. Why we prefer functional component over class based.
21. Explain the difference between class based and functional based component.
22. Why do we need to bind event handlers and in how many ways we can do it.
23. How can we pass methods as props.
24. How do we conditionally render react.
25. Explain the usage of list rendering and use of map in react.
26. Explain list as keys.
27. How do we handle forms in react.
28. Explain controlled or uncontrolled forms.
29. Explain component life cycle methods and different phases.
30. What are fragments and its different ways and also importance.
31. What are pure components and its importance.
32. Explain memo.
33. Explain refs and its importance with applications.
34. What is the use of forwarding refs.
35. Why do we need portals.
36. How do we handle react errors i.e error boundary.
37. Explain HOC with small example.
38. What are render props and its importance.
39. Explain the importance of context.
40. What is prop drilling.
41. How do we handle the http request in react.
42. What are reconcilliation.
43. What are hooks and its associated rules.
44. Why do we need hooks.
45. Explain the use of useState and its syntax.
46. Explain useState with array.
47. Explain useState with objects.
48. How useState works with the previous state.
49. What are useEffect.
50. Explain the working of useEffect.
51. How can we run effects conditionally.
52. Explain useEffects with cleanup.
53. Explain useEffect with incorrect dependency.
54. Explain data fetching in effects.
55. Explain context hook and its importance.
56. Why do we need useReducer.
57. How to use multiple useReducers.
58. Explain the data fetching in useReducer.
59. What is the difference between useState and useReducer.
60. Explain useCallback hook.
61. Explain useMemo hook.
62. Explain useRef hook.
63. What are custom hooks and how can we implement them.
64. Explain state immutability.
65. How to optimize react.
66. Explain the working of virtual dom and also figure out the differences from real dom.
67. Why do we prefer virtual DOM.
68. What are function creators.
69.Explain action , types and reducer.
70. Explain useHistory.
71. Explain useLocation.


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



