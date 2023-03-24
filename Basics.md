# PythonNotes
### Working Data
- <b>Data Types</b>
    - Variables: A labeled location in memory that is used to store a value.
    - Integers: A whole number.
    - Float: A number that has a decimal point.
    - Strings: Represents a string of text that must be enclosed in 'single' or "double" quotation.
- <b>Lists (Arrays)</b>: An orders sequence of data that usually share common attributes. Enclosed by [brackets]
    - One-dimensional list
    - Two-dimensional list
- <b>Sets</b>: Am unordered collection of unique data usually different attibutes. Enclosed by {curly brackets}
- <b>Tuples</b>: Similar to a list and is a sequence of data, each identified by an index. 
    - In contrast to lists, data in Tuples cant be changed once assigned, and can contain different types of data.
- <b>Dictionaries</b>: An unordered collection of items, each identified by a key.
- <b>Program Input</b>: Prompts user for input or retieve it from a file.
- <b>Program Output</b>: Idsplays results to user or write data to a file.
- <b>Casting Data</b>: Converts variables to different working data types.
    - Implicit Casting: Python automatically coverts one data to another data type.
    - Explicit Casting: Programmer converts the data type using this specific function.
        - int( ) converts data to an integer
        - long( ) converts data to a long integer
        - float( ) converts data to a floating point number
        - str( ) converts data to a string

### Modules
- Modules are python files that are part of a program. 
- Its best practice to split code into several files for easier maintenance and reusability. 
- These modules, contain code that can be imported into another program. 
- We can build a code library that contains a set of functions that you want to include when developing large applications.

### Importing Modules
- Python has built-in library of module you can import into your program. 
-  To import the modules into your code, use the import keyword
-  Each module has its own provate namespace which usually has the same name as the module, The namespace holds all the names of functions and variables declared in the module.
-  We must use dot(.) notation to refer to a particular module: moduleName.functionName()
-  turtle.forward(100) - turtle is the name of the module we imported earlier, and forward() is a function defined within the module.


