What is a ‘call’? function invocation
How many ‘calls’ can happen at once? one 
What does LIFO mean?Last In, First Out last function that gets pushed into the stack is the first to be pop out
Draw an example of a call stack and the functions that would need to be invoked to generate that call stack. 
function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();
What causes a Stack Overflow > when a function call itself repeatedly
What is a ‘refrence error’? using variable that isnt declared
What is a ‘syntax error’? cannot be parsed in terms of syntax
What is a ‘range error’?manipulate an object with some kind of length and give it an invalid length
What is a ‘tyep error’?  typing errors thta is incompatable 
What is a breakpoint? to put a debugger  statement in your code in the line you want to break.
What does the word ‘debugger’ do in your code? it breack the line of the code


