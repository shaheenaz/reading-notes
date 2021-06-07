## reading class 3

1. What does .map() return? it returns a new array with the same length of the orignal one
2. If I want to loop through an array and display each value in JSX, how do I do that in React? by embidding the expression into curly braces
3. Each list item needs a unique _key___.
4. What is the purpose of a key? it idenify which item has been added or chnged or removed




1. What is the spread operator? three dots to expand an iterable object into the list of arguments.
2. List 4 things that the spread operator can do.1-Copying an array 2-Concatenating or combining array 3-Using Math functions 4-Using an array as arguments
4. Give an example of using the spread operator to combine two arrays.
const myArray = [`🤪`,`🐻`,`🎌`]
	const yourArray = [`🙂`,`🤗`,`🤩`]
	const ourArray = [...myArray,...yourArray]
	console.log(...ourArray)

5. Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['🍏','🍊','🍌']
	const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
	console.log(fewMoreFruit) // Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

6. Give an example of using the spread operator to combine two objects into one.

const objectOne = {hello: "🤪"}
	const objectTwo = {world: "🐻"}
	const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
	console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
	const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
	objectFour.laugh()




1. In the video, what is the first step that the developer does to pass functions between components? create a function at smae level where the state is
2. In your own words, what does the increment function do? it increses the the count eveytime you click on the button 
3. How can you pass a method from a parent component into a child component? by usign props
4. How does the child component invoke a method that was passed to it from a parent component? by using this.props.the metod name(this.props.the info i want to pass )