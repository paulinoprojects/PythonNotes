# Flow Control
#### Importance of Flow Control
Programing is just a series of instructions, but programming’s real strength isn’t just running one instruction after another like a weekend errand list. Based on how expressions evaluate, a program can decide to skip instructions, repeat them, or choose one of several instructions to run.

Flow control statements can decide which Python instructions to execute under specific conditions. Before learning about flow control statements, first we need to learn how to represent yes (True) and no (False) options, and we need to understand how to write those branching points as Python code by understanding: <b>Boolean values, comparison operators, and Boolean operators</b>.

## Boolean Values
- Only 2 Values: True or False 
- Rules: 
  - Lack the quotes you place around strings
  - They always start with a capital T or F
  - Boolean values are used in expressions and can be stored in variables
  - True or False cannot be variable names
## Comparison Operators (Relational Operators)
- Compare two values and evaluate down to a single Boolean value, then your code continues based on the specific conditions. 
- https://www.youtube.com/watch?v=Vw2HxT5Wj-I
![Compaison Operators](https://user-images.githubusercontent.com/111991325/227411939-9dcbaa20-2239-41eb-bd2e-c3e39737c4d3.jpg)

## Boolean Operators
- Three Boolean operators: <b> AND, OR, NOT </b> 
- Like comparison operators, they evaluate these expressions down to a Boolean value
- The <b>AND</b> operator evaluates an expression to True <i>if both</i> Boolean values are True; otherwise, it evaluates to False. 
![Boolean AND](https://user-images.githubusercontent.com/111991325/227414639-0fd135a5-afc1-4fa2-98f4-0c06d577bb64.png)
- The <b>OR</b> operator evaluates an expression to True <i>if either</i> of the two Boolean values is True. If both are False, it evaluates to False.
![Boolean OR](https://user-images.githubusercontent.com/111991325/227415533-b84506d5-4317-4abf-b1ce-6577e83d6627.png)
- The <b>NOT</b> operator operates <i>only<i/> one Boolean value (or expression).The not operator simply evaluates to the opposite Boolean value.
![Boolean NOT](https://user-images.githubusercontent.com/111991325/227415811-04311aa3-3ca9-4356-a776-f7cb7d3ec591.png)

# Elements of Flow Control
  - Flow control statements often start with a part called the condition and are always followed by a block of code called the clause.
1. Conditions
    - Conditions is a specific name in the context of flow control statements. Conditions always evaluate down to a Boolean value, True or False.
    - A flow control statement decides what to do based on whether its condition is True or False, and almost every flow control statement uses a condition.
2. Blocks of Code (The Clause)
    - Lines of Python code can be grouped together in blocks. 
    - You can tell when a block begins and ends from the indentation of the lines of code. There are three rules for blocks.
      - Blocks begin when the indentation increases.
      - Blocks can contain other blocks.
      - Blocks end when the indentation decreases to zero or to a containing block’s indentation.
3. The program execution (or simply, execution) 
    - a term for the current instruction being executed. 
    - If you print the source code on paper and put your finger on each line as it is executed, you can think of your finger as the program execution.
4. Flow Control Statements
    - The most important piece of flow control is the statement hemselves.
    - They are the actual decisions your program will make.
    - Most common type of flow control statement is the <b>if statement</b>
  
 # If Statements
  
 
