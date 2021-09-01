# Putting it all together  

One of the many great parts of React is how it makes you think about apps as you build them. In this document, we’ll walk you through the thought process of building a searchable product data table using React.  

![](https://miro.medium.com/max/810/1*-rCt5QmwH7hLi8kGeq6kwA.png)

## Start With A Mock  :

- Step 1: Break The UI Into A Component Hierarchy    

The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names  
 
 ![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3QlNEiCnjwuXkIRUl7Yn77AsMKJ_tjP-GL27OfHtXZKDZ1l63HV_gOIOI-9ezGdOsaew&usqp=CAU)

- Step 2: Build A Static Version in React   

The easiest way is to build a version that takes your data model and renders the UI but has no interactivity. It’s best to decouple these processes because building a static version requires a lot of typing and no thinking, and adding interactivity requires a lot of thinking and not a lot of typing.  

To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.

- Step 3: Identify The Minimal (but complete) Representation Of UI State:  

To make your UI interactive, you need to be able to trigger changes to your underlying data model. React achieves this with state.  

To build your app correctly, you first need to think of the minimal set of mutable state that your app needs  

*__Ask three questions about each piece of data:__*

1. Is it passed in from a parent via props? If so, it probably isn’t state.
2. Does it remain unchanged over time? If so, it probably isn’t state.
3. Can you compute it based on any other state or props in your component? If so, it isn’t state.

- Step 4: Identify Where Your State Should Live  

 Remember: React is all about one-way data flow down the component hierarchy. It may not be immediately clear which component should own what state. This is often the most challenging part for newcomers to understand   

 - Step 5: Add Inverse Data Flow  

 So far, we’ve built an app that renders correctly as a function of props and state flowing down the hierarchy.

React makes this data flow explicit to help you understand how your program works, but it does require a little more typing than traditional two-way data binding.


