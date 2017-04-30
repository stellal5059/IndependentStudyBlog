#Finishing up Unit 1
---
## Self-Assessment

~ This is something that we all do usually at the end of the year or the end of a great project. We take the time to look over our code before doing anything with it whether it’s deploying it on heroku or making it live through C9. Usually when we self-assess our code we look for correctness and completeness.

~When you self-assess one of your own projects there are certain things you would have to take into consideration:

	~ Is there any syntax errors the computer cannot read/understand
	
	~ If you were to give this to someone else would they be able to understand the purpose of the project without having to press run that means is the code readable along with the comments
	
	~Does my code do what it is supposed to do?
	
	~Is my code complete?
	
	~Does my code satisfy the project or assignment goals?

~ Consider Both the Objective(facts) and subjective(how would a human look at it) perspectives 

~Evaluating correctness of a code focuses mainly on what the code does, correct code is free of bugs and errors(if done correctly)

### Self-Assessment in Earsketch
~ When creating a song, if there is a lack in sections (such as transitions), the listener will be able to notice due to to the very abrupt changes

~Correctness and Completeness of a code is determined by the way it runs, does it run the way it’s supposed to?

---

# Going through Unit 2

~ When computer scientists and software engineers work hard on their code there main goal is to make it clear and concise (“work smarter not harder” ~Mr.Mueller). Going through the 4 years in software engineering the one thing we were always taught was to work smarter not harder. The more efficient the code and the easier it is to understand the easier it is to make changes and find bugs if necessary. 
 
        Taken from my notes → 


---
## Looping

~ Repetition is important in music especially when it comes to creating the chorus of a song. The way a computer repeats statements/concepts is through the use of a loop.

~ A common loop used in JavaScript is a for-loop which says take this section of code and repeat it for this amount of times.

	```JavaScript
	/variable for the counter; condition to check for; increase by 1 after each runthrough
		For(var i=0; i<2; i++){
			//code want to be repeated
			}
	```
	
Components in a `for-loop`

~Loop Body: The code that the loop will keep running repeatedly (chorus of a song)

~Initialization: The variable at the start of the loop, this will be set once the loop starts and will keep track of how many times the loop has run. Will help when checking the status of the conditional.

~Loop condition: Checks whether the code should continue or not; will allow the code to continue once the loop has finished. 

---
### Interpreting a script
~ The way a script is read is the order it will run, read line by line, top to bottom, once the line gets to the end of the code then it will jump back to the start of the code and will be read the same way; aka Control Flow

---
### Sections and Form
Musical Form and Custom Functions

~ A section is a musical unit, this consists of several measures that expresses an idea or a feeling. Intros, Verses, Choruses and Outros are examples of sections that contribute to the form of a song.

~ A really common form of a song is A-B-A:
    
    ~A refers to the familiarity of the song, 
    ~B adds variety to the song

### Custom Functions
~Custom Functions allow you to write your own function and avoiding repetitive code, they can be placed anywhere in the script and can be named anything you would like, with as many parameters as you would like
```JavaScript
		Function anyName(parameter(s)){
	//code
}
```
## Abstraction

~When programming we create abstractions, the same way we group musical ideas into sections. An abstraction is grouping the ideas to form a single concept, in computer science we use functions for abstraction since they take multiple statements and put them into one tool. Abstraction can also help decrease the complexity of the program (work smarter not harder), they can make the form more clear and efficient, this is beneficial when it comes to writing and debugging larger programs.

## How to upload your own sounds to Earsketch
    ~Click on “Add Your Own Sound”
        ~Choose the file you would like to upload from your computer
        ~Quick Record allows you to record clips directly to your library
### Processes and Memory
~ The Central Processing unit (CPU) is the part of the computer that is given the code (insructions) on what to do and how to run, this is a complex electronic circuitry that is able to run this set of instructions. 

~This is also known as the control center for the computer, modern day computers have multiple running at one time which is what makes more modern computers faster than the ones that were first invented. The ones that were first invented could only run one process at a time

~A computer’s memory holds data and instructions for the CPU. Memory is also known as the primary storage or RAM (random access memory), the RAM only stores data and instructions temporarily. The Memory allows for fast access even though it is not a long-term storage unit. Another form of storage is the secondary storage, this is also known as the hard-drive or cloud. The secondary storage is where the volume levels are stored even when the computer is shut down. 

~Sometimes data is put into memory for the CPU to use comes from an input device rather than the secondary source

~Inputs: signals or data received by the computer 

~Outputs: How the computer communicates with the outside world

## Beat Patterns with Strings
~can use makeBeat() to create rhythmic patterns; aka beat patterns; A character is a single unit of informations, this can be a letter, number, whitespace, punctuation or symbol. The order of the characters allow you to be able to music and clips.

### makeBeat()
~makeBeat() takes in four arguments:

	~Clip Name
	~Track #
	~ Measure Number: makeBeat() only requires the first measure, the length will determine the end measure
    ~Beat String 
    
~Creating an interesting beat is important and you would like to have control over how many times it plays throughout the song. Rather than making a line for every measure you would like to have it on you can use a for-loop


### Return Statements
~Return statements are in almost every coding language out there, what it does is it gives back whatever it is attached to, usually put at the end of the code. 

~How a return statement works is:

	~ It takes in an input
	~Runs through the functions
	~Returns the output
~Functions don’t always have to include return statements, they are mainly useful when debugging code (check out week 3). Once a function sends the output then that will be the signal to stop, anything after that return value will be ignored. Recommended use: at the end of the code or for debugging purposes

### Substrings
~ Also known as a slice, a substring only occurs inside of a larger string and allows a beat to be sliced up throughout the song, this is usually for EDM (electronic dance music) and remixing

    Syntax: 
    ```JavaScript
    
    oldString.substring(Start, End);
  
    ```
---

# Take-Aways

* When taking notes put stuff into your own words, if you were to copy word for word you would not be able to actually understand what you're learning