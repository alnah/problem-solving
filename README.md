# problem-solving
Mindset inputs for problem solving and good outputs.

## UPPI: understand, plan, pseucode, implement

1. Understand  
    - Rephrase in plain English  
    - Sketch up diagrams  
2. Plan  
    - Interface  
    - Inputs  
    - Output  
3. Pseudocode  
    - Steps  
4. Implement  
    - Break down into smaller problems  
    - Resolve one-by-one  
    - Keep going on

## Think before writing code

- Variable : a place in memory to store data called name of type type that starts with the value initial value  
	- name: what do we call this thing?
	- type: what type of data does it contain?
	- init: what is it's starting value?
- Please write initial values thinking as states, it will be clearer for future you, people reading and also to start thinking dynamic programming instead of static programming. Declare it void first, then store something. Python, like Ruby, is dynamic typed like super very easy going which is cool and bad, and the risk is not to learn those things very important when you'll have to deal with other trendy languages just like JS, or Rust, for instance, or even prompt engineering in Python.

- Input : ask the user message and store the answier in a variable  
	- variable: where the answer from user will be stored?
	- message: question being asked to the user?

- Output: output the text message.  
	- message: what text to write to the user?

- for…loop: begin with a sentry at start and change to sentry on each pass until sentry is larger than or equal to finish.  
	- sentry: integer variable that will control loop
	- start: integer value of sentry at beginning
	- end: integer value of sentry at end
	- change: integer to add to sentry at each pass

- while…loop: initialize sentry with initialization code then continue loop as long as condition is true. Inside loop, change sentry with change code.  
	- sentry: variable that will control loop
	- init: code that initalizes sentry
	- condition: loop repeats if condition is true
	- change: code to change sentry so condition cana be triggered
- Note the syntax only requires a condition. Good logic requires much more. This is why while loops can be such notorious problems when you start to implement them.

- function: an unique action peformed that receive arguments instead of the defined parameters that stands as placeholders of a certain type that might give back a return value with a certain type or create a side-effect acting in a specific scope.  
	- action: what is the unique action performed defining the name?
	- parameters: what are the placeholders names for arguments?
	- return value or side-effect: is it going to return a value or not?
	- type: what are the data types form?
	- scope: variables used are global, local? is it an inner function?

## Problems
- exceptions and error messages are your friends!
- they are opportunies to grow
- this is a normal part of programming
- it's pretty much all about debugging
- did you tell computer what to do incorrectly? (Syntax)
- did you tell computer to do the wrong thing? (Logic)
- most beginners assume it's an implementation problem
- usually it's really an algorithm problem

## Debugging
- the best way to debug is to not have bugs and program defensively
- bad code can be googled
- bad algorithms usually cannot...
- what are you not understanding?
- what tools can you use?
- DON'T start with a solution, you're gonna fuck you up.
- your assumptions might be not true!
- start by truly understanding the problem.
- look up to find a tool to help you.
