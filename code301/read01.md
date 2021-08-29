#  Introduction to React and Components  

## Component-Based Architecture
Component-based architecture focuses on the decomposition of the design into individual functional or logical components that represent well-defined communication interfaces containing methods, events, and properties. It provides a higher level of abstraction and divides the problem into sub-problems, each associated with component partitions.

![](https://hackernoon.com/hn-images/1*HSisLuifMO6KbLfPOKtLow.jpeg)

## What is a Component?
`A component` is a modular, portable, replaceable, and reusable set of well-defined functionality that encapsulates its implementation and exporting it as a higher-level interface.

A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

A software component can be defined as a unit of composition with a contractually specified interface and explicit context dependencies only. That is, a software component can be deployed independently and is subject to composition by third parties.  

### Views of a Component
* Object-oriented view
* Conventional view
* Process-related view  

![](https://www.edureka.co/blog/wp-content/uploads/2017/08/UI-Tree.png)
### Characteristics of Components
* **Reusability** − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

* **Replaceable** − Components may be freely substituted with other similar components.

* **Not context specific** − Components are designed to operate in different environments and contexts.

* **Extensible** − A component can be extended from existing components to provide new behavior.

* **Encapsulated** − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

* **Independent** − Components are designed to have minimal dependencies on other components.  

### Advantages of using component based architecture
* Ease of deployment 

* Reduced cost 

* Ease of development 

* Reusable

* Modification of technical complexity 

* Reliability 

* System maintenance and evolution 

* Independent  


## What is Props?
React is a component-based library which divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props.

“Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

But the important part here is that data with props are being passed in a uni-directional flow. (one way from parent to child).

Furthermore, props data is read-only, which means that data coming from the parent should not be changed by child components.  

![](https://miro.medium.com/max/1138/1*27LtOtFyJe7MguQkNcZQjQ.png)
### Using Props in React
I will be explaining how to use Props step by step.
* Firstly, define an attribute and its value(data)
* Then pass it to child component(s) by using Props
* Finally, render the Props Data  

*class ParentComponent extends Component {  *  
  *render() {*  
   *return (*    
      *< h1>*    
       *I'm the parent component.*  
        *< ChildComponent />*  
      *< /h1>*  
    *) ;*  
  *}*  
*}*  

And this is our ChildComponent:

*const ChildComponent = () => {*  
  *return < p>I'm the 1st child!< /p>;*   
*};*    

Understanding React’s approach to data manipulation takes time. I hope my post helps you to become better in React. If you have any questions, comment down below. Next, you can read how to manage data with another special React feature: State.