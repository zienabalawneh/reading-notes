# Debugging

# JS book

## Ch. 10: “Error Handling & Debugging”

#### ORDER OF EXECUTION 

+ To find the source of an error, it helps to know how scripts are processed. The order in which statements are executed can be complex; some tasks cannot complete until another statement or function has been run

## THE STACK

+ The JavaScript interpreter processes one line of code at a time.

1. When a statement has to call some other code in order to do its job, the new task goed to the top of the pile of things to do .

2. once the new task has been performed , the interpreter can go back to the task in hand .

3. Each time a new item is added to the stack ,it creates a new execution context.


## EXECUTION CONTEXT & HOISTING 

+ Each time a script enters a new execution context, there are two phases of activity: 
  1. PREPARE

     01. The new scope is created 
     02. Variables, functions, and arguments are created 
     03. The value of the this keyword is determined 

  2. EXECUTE

    01. Now it can assign values to variables 
    02. Reference functions and run their code 
    03. Execute statements 


## UNDERSTANDING ERRORS 

+ If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code. 

## UNDERSTANDING SCOPE

+ In the interpreter, each execution context has its own variables object. It holds the variables, functions, and parameters available within it. 
Each execution context can also access its parent's variables object. 

## HANDLING EXCEPTIONS 

`try{`

`// try to execute this code` 

`}catch(exception){`

` // if there is an exception ,run this code`

`}finally{`

  `  //this always gets executed `
`}`



The **try** statement lets you test a block of code for errors.

The **catch** statement lets you handle the error.

The **throw** statement lets you create custom errors.

The **finally** statement lets you execute code, after try and catch, regardless of the result.

