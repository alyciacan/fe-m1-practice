## Ch 3 Qs
1. If we have a function defined as function sayHello(){console.log("Hello!")}, what is the difference between entering sayHello and sayHello() in the console?
  Typing `sayHello` won't call the function (i.e., the function won't be prompted to run), whereas adding the () will call the function.
2. What is the difference between function parameters and arguments?
   A function may take _parameters_, which are what get entered in the () when a function is called, and are the information that the function needs to run. Each value that is entered as an argument is an _argument_.
3. What is the keyword return used for?
   `return` tells the interpreter to take some value back to the code that called the function. It also sends the interpreter back to the statement that called it, meaning that any subsequent code in the function won't run.
4. How are local variables better than global variables?
    Global variables can slow a page down, because the page needs to "remember" the global variable values the entire time the page is loaded. Also, global variables can lead to naming collisions (because two variables can't have the same name at the same time). Local variables avoid these issues.

  5. Are there instances you can think of where you might want to use a variable that is globally scoped over local?
     I'm not sure, but it seems that if a webpage requires a user to log in, the user's account number or username may need to be a global variable, so that the user doesn't need to keep logging in to use different apps within the same page. 
