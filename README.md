# javascript-exercises-6
Functions are the tiny building blocks that we can string together to make fully functional applications. Each function has a specific job to do and collectively run the program smoothly.

A function starts with the function keyword. This tells whatever is running your program that what follows is a function and o treat it as such.  Next is the function name. Give names to your function that describe what the function will do. Then an open and closed parenthesis. Finally open & closed braces. In between these braces is where all of the function code goes. 

For example: 
    function logsClassmates() {
        console.log('Michael');
}

logsClassmates();

Above we declare a function logsClassmates and set it up to console.log 'Michael'. We can see that in order to run this function, we need to write or invoke its name with the parentheses after it. This is the syntax to run a function. A function always needs parentheses to run.

Parameters: A function parameter will represent the data we pass into a function, for use in the function. Essentially, when we write a function we assign the data a variable names, even without knowing what the data will be. We set these variables inside of parentheses when we write the function. There is no limit to the amount of parameters we can include in a function, but each variable name must be separated by a comma. We can then use these variables within our function just as we wold any other variable.

For example:
    function myFunc(parameter1, parameter2,parameter3){
    }

Arguments: Once we have our parameters set up n our function, we can now pass data nto the function. We use the parentheses when we call the function. They're called arguments. Arguments can be ANY data type (string, number, Boolean, object, array, even other functions!). However, you should know which data type the function expects. To use an argument just put the data in the function call parentheses:

For example:
    function logsClassmates(name) {
        console.log(name);
    }
    logsClassmates('Joe')     //console.logs: Joe
    logsClassmates('Janie')   //console.logs: Janie

    To call the function to run you must write out the:
    function name('argument1 {must match parameter1}') this describes above 2 lines and how they're written.
    