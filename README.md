# reading-notes
class02
Life Cycle 

Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?     ther render is happens first   
These methods are called in the following order when an instance of a component is being created and inserted into the DOM:

constructor ( )
getDerivedStateFromProps( )
render( )
componentDidMount( )
What is the very first thing to happen in the lifecycle of React? Constructor    (When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.)
Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates ? 1-constructor 2-render 3-componentDidMount 4-componentWillUnmount
What does componentDidMount do? The componentDidMount() method allows us to execute the React code when the component is already placed in the DOM (Document Object Model). This method is called during the Mounting phase of the React Life-cycle i.e after the component is rendered.
React State Vs porps

    
What is the big difference between props and state?
 Can get initial value from parent Component?    Yes     Yes
    Can be changed by parent Component?             Yes     No
    Can set default values inside Component?*       Yes     Yes
    Can change inside Component?                    No      Yes
    Can set initial value for child Components?     Yes     Yes
    Can change in child Components?                 Yes     No
