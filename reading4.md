1. What is a ‘Controlled Component’? An input form element whose value is controlled by React 
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why. we update the state because the handle runs on every keystroke to update the React state, the displayed value will update as the user types.
3. How do we target what the user is entering if we have an event handler on an input field?we can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.




4. Why would we use a ternary operator? for the conditons such as if statment to test of true or false and do the condition
5. Rewrite the following statement using a ternary statement

x===y ? true : false