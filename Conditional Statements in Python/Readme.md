Experiment 6 - Conditional Statements in Python

Name-Bedang Das
PRN-25070123031
Batch-A2


Conditional statements are the decision-makers of a code. They allow a program to perform a certain set of operations depending upon whether the condition is true or not.
Aim:

To study the conditional statements in Python
Tools used:

Google Colab or Jupyter Notebook
Theory:

A conditional statement is a construct that performs different computations or actions depending on whether a programmer-specified boolean constraint evaluates to true or false. In Python, this is the primary mechanism for breaking the linear execution of code, allowing the program to respond dynamically to input variables.

Types of Conditional Statements:

(i)The Simple Branch:
        This is the simplest form of control flow. If the condition is true, it executes a block of code. If the condition is not true, then it exits from the block and continues to execute the rest of the code.

(ii) The Bi-Directional Branch:

        This has a maximum of two conditions. If the given condition is true, it executes a block of code; if not, it jumps to the else block and executes that block of code.

(iii) The Multi-Way Branch: 

        This has 2 or more than 2 conditions. It includes the commands 'if,' 'elif,' and 'else.' When the code is run, it checks for the first condition. If the condition checked is not true, then it goes and checks the next condition. Until and unless all the conditions turn out to be false, it keeps on checking each and every condition until it reaches the else block.

(iv) Nested - If:

        It has one if condition inside another if condition. Only if the outer if condition is true does it execute the if condition inside, or else it doesn't execute. Here only one condition can be true, i.e., mutually exclusive.

(v) Multiple - If:

        It has multiple if conditions below one another. When the program is run, each and every "if" condition is checked no matter whether the condition is true or not. Here, multiple conditions can be checked.

The Boolean Predicate:

At the heart of every conditional is the predicate—an expression that yields a value in the set True , False . Python evaluates these using:

--> Relational Operators: Evaluation of magnitude or equality ( < , > , == , ! = ).

--> Logical Operators: Boolean algebra gates (and, or, not) used to combine multiple predicates.

--> Truthiness: Python’s unique ability to evaluate non-boolean objects (like lists or integers) as boolean values. For instance, an empty list [] evaluates to False.
Learning Outcomes:

    There are three commands that can be used in conditional statements: if, elif, and else.

    While writing the commands mentioned above, a semicolon (:) must be used at the end. While proceeding to the next line, a small space will be present at the start of the line, which is called "indentation."**

    In Python, if indentation is not there, it shows an error.

    The else statement is not compulsory in the conditional statement, but it is used as a safety block of code.

Applications of lists:

    Automated Control Systems: Conditional statements are used to maintain homeostasis* in a system.

    Automotive Safety Systems: Real-time embedded systems in cars use conditionals to make split-second decisions.

    It is used for fraud detection* in financial technology.

Advantages:

    Dynamic Decision Making: It has the ability to handle various inputs at the same time. Without conditionals, programs would be "static," performing the same task regardless of the data.

    Error Handling and Robustness: Conditionals allow for guard clauses, which prevent a program from crashing when it encounters bad data.

    Flexibility via "Truthiness": Python allows you to check for the existence of data without formal comparisons.

Conclusion:

Thus various types of conditional statements are executed in Python and the output is verified.
