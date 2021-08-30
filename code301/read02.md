# State and Props  

## React: Component Lifecycle Events  

### What are component lifecycle events?
React lets you define components as classes or functions. The methods that you are able to use on these are called lifecycle events. These methods can be called during the lifecycle of a component, and they allow you to update the UI and application states.

![](https://miro.medium.com/max/2000/0*0saPKFiTUk6W3FYp)  

Mounting, Updating, and Unmounting are the three phases of the component lifecycle.  

* Mounting  :  
When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.  

* Updating  :  
Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.
static getDerivedStateFromProps, shouldComponentUpdate, render,
getSnapshotBeforeUpdate, componentDidUpdate, UNSAFE_componentWillUpdate, UNSAFE_componentWillReceiveProps

* Unmounting  :  
The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.

* constructor()  :  
The constructor for a React component is called before it is mounted.If the component is a subclass you should call super(props), or the props will be undefined. constructors can be used to assign state using this.state or to bind event handle methods to an instance.   

*  componentDidMount()  :  
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().
setState() can be called here, but it should be used sparingly, because it will cause a rerender, which can lead to perfomance issues.
Here we use componentDidMount() to connect to the YouTube API and get videos when the components is rendered.  

* componentWillUnmount()  :  
This method allows you to clean up the DOM and netwrok requests/ subscriptions.

## The big difference between props and state:  

Props and state are related. The state of one component will often become the props of a child component. Props are passed to the child within the render method of the parent as the second argument to React.createElement() or, if you're using JSX, the more familiar tag attributes.

< MyChild name={this.state.childsName} />
The parent's state value of childsName becomes the child's this.props.name. From the child's perspective, the name prop is immutable. If it needs to be changed, the parent should just change its internal state:

this.setState({ childsName: 'New name' });  

and React will propagate it to the child for you. A natural follow-on question is: what if the child needs to change its name prop? This is usually done through child events and parent callbacks. The child might expose an event called, for example, onNameChanged. The parent would then subscribe to the event by passing a callback handler.

< MyChild name={this.state.childsName}   
onNameChanged={this.handleName} />  

The child would pass its requested new name as an argument to the event callback by calling, e.g., this.props.onNameChanged('New name'), and the parent would use the name in the event handler to update its state.  


handleName: function(newName) {  
   this.setState({ childsName: newName });  
}  