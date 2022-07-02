## Ch 2 Qs
1. How do you declare a variable. What does the equals sign really mean in JavaScript? What is it called in JavaScript?
   To declare a variable: `var variableName`. You can assign a value to the variable using an _assignment operator_ (=). The assignment operator really means "is assigned to", not "equals".
2. There are three big data types in JavaScript: numbers, strings, and booleans. Describe what each of them are.
   __Numbers__ contain only numbers, although they can be positive, negative, or decimals.
   __Strings__ can contain letters, numbers, and symbols.
   __booleans__ can only contain either "true" or "false".
3. What are the six rules for naming variables? What are a few JavaScript reserved words that you should avoid using for variable names?
   a) Don't use key or reserved words e.g., `var`.
   b) Names are case sensitive. Don't give two variables the same name with different cases (e.g., array and Array).
   c) Variable names can start with letters, $, or _.
   d) Variables can contain all of the above plus numbers.
   e) Variable names should describe the type of data they contain.
   f) Variable names that contain >1 word should be written using camelCase.
4. How can an array be useful when dealing with multiple related values? How do you access/change a value in an array?
    Arrays are great because they can hold as many values as we need them to. To access a value: arrayName[#], using the index of the value you need in []. To change a value in the array, simply use the assignment operator. E.g., arrayName[3] = 44 will assign or reassign the 3rd index in arrayName to 44.
5. What is the difference between an expression and a statement?
    An __expression__ is a unit of code that resolves to a value (e.g., var age = 40;). A __statement__ performs or controls an action but doesn't resolve to a value.
6. What are three types of operators and how are they used?
    a) + is a string operator and concatenates two strings together. 
    b) = is an assignment operator and is used to assign a value to a variable.
    c) || is a logical operator and evaluates to true if one of the conditions on either side of it is true.
