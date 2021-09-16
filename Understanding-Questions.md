# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* The onClick handler gets called  
* THe onClick handler dispatches the applyNumber action
* an action object is created based on the input 
* the current state & object gets passed into the reducer
* then the action is processed and a new state is created
* the component is then rerendered with the new state loaded in displaying the 1
* TotalDisplay shows the total plus 1.

