1. proptypes throw an error to the console if the types of your props differ from what you've specified. javascript is a weakly typed language, and when you're working in a big react project with other developers, passing around props of the wrong type by accident is common.  not only that, but the proptypes expression in each component file is a handy way for other developers to see the types data your components are expectring.

2. lifecycle events are stages in a component's existence (mounting, updating, unmounting) that are pegged to built in functions in react that allow us to execute code at certain stages during  component's cycle. 

3. a higher order component is a function that receives a component as an paramater and returns a new component.

4. 
a) css preprocessor
-total control

b) ui library
-easy, incredibly quick, components are already built for you
-looks like everything else, not original
-limitations such as only being able to access certain selectors to style

c) styled components
-very easy to work with, easy syntax
-can use real css syntax, don't have to avoid -'s 
-makes it easy to build an internal component library