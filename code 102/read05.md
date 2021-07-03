# JavaScript's

![Java script](https://www.bbvaapimarket.com/wp-content/uploads/2015/09/bbva-open4u-herramientas-programacion-javascript.png)


## JavaScript's Operators
`JavaScript` has the following types of operators. This section describes the operators and contains information about operator precedence.

* [Assignment operators](https://www.w3schools.com/js/js_assignment.asp)  
* [Comparison operators](https://www.w3schools.com/js/js_comparisons.asp)  
* [Arithmetic operators](https://www.w3schools.com/js/js_arithmetic.asp)  
* [Bitwise operators](https://www.w3schools.com/js/js_bitwise.asp)  
* [Logical operators](https://www.w3schools.com/js/js_comparisons.asp)   
* [String operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#string_operators)  
* [Conditional (ternary) operator](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#conditional_ternary_operator) 

![javascript operators](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/03/JavaScript-Operators-1200x720.jpg)

#

### Assignment operators:
`Example`  
*x = y*  
*x = y*  
#

### Comparison operators:

Operator 	|  Description  |  Examples returning true |
--------- | ------------  | --------|
*Equal (==)*|Returns true if the operands are equal. |	*3==var1, "3"==var1,  3=='3'*|
*Not equal (!=)*|	Returns true if the operands are not equal.|	*var1 != 4,   var2!="3"*|
*Strict equal (===)*|	Returns true if the operands are equal and of the same type. |*	3===var1* |
*Strict not equal (!==)*|	Returns true if the operands are of the same type but not equal, or are of different type.|* var1!=="3",   3!=='3'*|
*Greater than (>)*|	Returns true if the left operand is greater than the right operand.	| *var2>var1, "12">2*|
*Greater than or equal (>=)*	| Returns true if the left operand is greater than or equal to the right operand.	| *var2>=var1, var1>= 3*|
*Less than (<)* |Returns true if the left operand is less than the right operand.|*var1<var2,  "2"<12*|
*Less than or equal (<=)*|	Returns true if the left operand is less than or equal to the right operand.|	*var1<=var2, var2<=5*|  
#

### Arithmetic operators : 
An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value.  
The `standard` arithmetic operators are:  
* addition (+)  
* subtraction (-)  
* multiplication (*)  
* division (/) 

These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces `Infinity`:
 ).  

 `For example`:

*1 / 2; // 0.5  
1 / 2 == 1.0 / 2.0;*  
 // **this is true**  
 
 Operator	|  Description |	Example|
  --------------| ---------------- | -------------|
Increment (++)|	Unary operator. Adds one to its operand.If used as a prefix operator (++x), returns the value of its operand after adding one; if used as a postfix operator (x++), returns the value of its operand before adding one.|  	If x is 3, then ++x sets x to 4 and returns 4, whereas x++ returns 3 and, only then, sets x to 4.|
Decrement (--)|	Unary operator. Subtracts one from its operand. The return value is analogous to that for the increment operator.	|If x is 3, then --x sets x to 2 and returns 2, whereas x-- returns 3 and, only then, sets x to 2.|  

 #

### Logical operators :   

Operator |	Usage |	Description  |
---------- | -----  | ----------   |
Logical AND (&&) |	*expr1 && expr2* |	Returns expr1 if it can be converted to false; otherwise, returns expr2. Thus, when used with Boolean values, && returns true if both operands are true; otherwise, returns false.|
Logical OR |	*expr1 or expr2* |	Returns expr1 if it can be converted to true; otherwise, returns expr2. Thus, when used with Boolean values, or returns true if either operand is true; if both are false, returns false.|
Logical NOT (!)|	*! expr*	| Returns false if its single operand that can be converted to true; otherwise, returns true.

#
### String operators:  
In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.

 `For example`:  
*console.log**('my ' + 'string')*; // **"my string"**.  
#
#
## JavaScript Loop :  
`JavaScript` Loops or looping repeat a piece of code till the particular condition meets. Thus a loop will run a code block again and again till condition is matched.

`Loops` offer a quick and easy way to do something repeatedly.  

![JavaScript Loop](https://tutorial.techaltum.com/images/javascript-loops.jpg)  
#

### Most important type of loops in JavaScript :
* While Loop  
* Do While Loop  
* For Loop  

**while statement :**   
A `while` statement executes its statements as long as a specified condition evaluates to `true`. A while statement looks as follows:

while (condition)  
   statement  

If the `condition` becomes `false`, statement within the loop stops executing and control passes to the statement following the `loop`.

The condition test occurs before statement in the loop is executed. If the condition returns `true`, statement is executed and the condition is tested again. If the condition returns `false`, execution stops, and control is passed to the statement following `while`.

To execute multiple statements, use a block statement ({ ... }) to group those statements.  

![While statment](https://media.geeksforgeeks.org/wp-content/uploads/20191118164726/While-Loop-GeeksforGeeks.jpg)

`Example 1`  
The following while loop iterates as long as n is less than 3:

`let` n = 0;  
`let` x = 0;  
`while` (n < 3) {  
  n++;  
  x += n;  
}  

With each `iteration`, the `loop` increments **n** and adds that value to **x**. Therefore, **x** and **n** take on the following values:  

After the first pass: *n = 1 and x = 1*  
After the second pass: *n = 2 and x = 3*  
After the third pass: *n = 3 and x = 6*  
After completing the third pass, the `condition` *n < 3* is no longer `true`, so the `loop` terminates.  
  
  #
**do...while statement**  
The `do...while` statement repeats until a specified condition evaluates to `false`.

A `do...while` statement looks as follows:

*do  
  statement  
while (condition);*  

statement is always executed once before the `condition` is checked. (To execute multiple statements, use a block statement ({ ... }) to group those statements.)

If condition is `true`, the statement executes again. At the end of every execution, the `condition` is checkedcondition. When the `condition` is `false`, execution stops, and control passes to the statement following `do...while`.

![do...while statement](https://media.geeksforgeeks.org/wp-content/uploads/20191118154342/do-while-Loop-GeeksforGeeks2.jpg)

`Example`    
In the following example, the do `loop` iterates at least once and reiterates until `i` is no longer less than `5`.

`let` i = 0;  
`do` {  
  i += 1; *console.log(i)*;  
} `while` (i<5); 

#
**for statement**  
A for `loop` repeats until a specified condition evaluates to `false`.

*for( initialization; condition; step value ){  
    code block;  
}*


for `loop` starts with for keyword followed by parenthesis. Initialization, condition and step values are inserted inside. Initialization is declared inside for `loop`. If the `condition` is ok, only then the `loop` will continue.

![For statement](https://media.geeksforgeeks.org/wp-content/uploads/20191108131134/For-Loop.jpg)

`For Loop Example`  

    for( var i=2; i<=20; i=i+2){
      document.write(i);
    }    

The above for `loop` starts from 2 and the condition is *i<=20*.

*i=i+2* will `increase` the value of **i** by **2**.

value of i is printed only if `condition` is matched.

The above `loop` will return Table of 2.

* Initialization, condition and `increment` are compulsory in for loop``.  
* if `increment` is missing, loop will runs Infinitely .  
* If *i=12*, and `condition` is *i<=10*, `loop` will not work.  

***@Amer Alqnahrah***

Thanks to all staff that don't save any effort to help us.