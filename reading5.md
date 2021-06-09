## class 5
How would you break a mock into a component heirarchy?  darw boxes around each component and subcompoonent and give them names 
What is the single responsibility principle and how does it apply to components?a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.
What does it mean to build a ‘static’ version of your application?to build a version that takes your data model and renders the UI but has no interactivity.
Once you have a static application, what do you need to add? we most use props and nevr use state
What are the three questions you can ask to determine if something is state? if it can update , change ,or initialize component 1- Is it passed in from a parent via props? 2- Does it remain unchanged over time? 3- Can you compute it based on any other state or props in your component? if the answer is no its not state then.

How can you identify where state needs to live? 1- Identify every component that render somthin 2-Find a common owner component 3- the common owner or another component higher up in the hierarchy should own the state 4- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.