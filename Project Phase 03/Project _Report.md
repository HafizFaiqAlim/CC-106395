#CC_106395: Mini java Compiler#

###PROJECT MEMBER###
StdID | Name
------------ | -------------
*61658* | *Hafiz Faiq Alim*

## Project Description ##
Its a compiler on Mini java language in which u will give GRAMMER as input and then it will compile it and give an output.

##Sample Language Used ##
mini java

#include <some code examples.h>
Language Selected 
*Mini Java*

```
Example of main constructs public static void main(String[] args)

Example of for loop constructs class ForLoopExample {

public static void main(String args[]){

 for(int i=10; i>1; i--){
 
      System.out.println("The value of i is: "+i);
   }
  }   
}
```
###Lexical Specification###
Variable names can have alphanumerical characters and underscores. An identifier may begin with a character or an underscore. It may not begin with a number. Java literals A literal is a textual representation of a particular value of a type. Literal types include boolean, integer, floating point, string, character, and date. Technically, a literal will be assigned a value at compile time, while a variable will be assigned at runtime. Java operators An operator is a symbol used to perform an action on some value. Operators are used in expressions to describe operations involving one or more operands.


```/ % ^ & | ! ~ = += -= *= /= %= ^= ++ -- == != < > &= >>= <<= >= <= || && >> << ?: Java separators A separator is a sequence of one or more characters used to specify the boundary between separate, independent regions in plain text or other data stream. [ ] ( ) { } , : ; ```


###Grammar###
MiniJava Grammar Program ::= MainClass ( ClassDeclaration )* MainClass ::= "class" Identifier "{" "public" "static" "void" "main" "(" "String" "[" "]" Identifier ")" "{" Statement "}" "}" ClassDeclaration ::= "class" Identifier ( "extends" Identifier )? "{" ( VarDeclaration )* ( MethodDeclaration )* "}" VarDeclaration ::= Type Identifier ";" MethodDeclaration ::= "public" Type Identifier "(" ( Type Identifier ( "," Type Identifier )* )? ")" "{" ( VarDeclaration )* ( Statement )* "return" Expression ";" "}" Type ::= "int" "[" "]" | "boolean" | "int" | Identifier Statement ::= "{" ( Statement )* "}" | "if" "(" Expression ")" Statement "else" Statement | "while" "(" Expression ")" Statement | "System.out.println" "(" Expression ")" ";" | Identifier "=" Expression ";" | Identifier "[" Expression "]" "=" Expression ";" Expression ::= Expression ( "&&" | "<" | "+" | "-" | "" ) Expression | Expression "[" Expression "]" | Expression "." "length" | Expression "." Identifier "(" ( Expression ( "," Expression ) )? ")" | <INTEGER_LITERAL> | "true" | "false" | Identifier | "this" | "new" "int" "[" Expression "]" | "new" Identifier "(" ")" | "!" Expression | "(" Expression ")" Identifier ::=

##Problems Faced##
alot of problems were faced in a row as we are totally freshess for the flex and its not a bed of roses to use flex as compared to other programming languages but as sir has given motivation and efforts we have somehow managed to built a project

###Problem 1: GET TO KNOW GITHUB###
It was really difficult to work on github but now I have learn't alot by watching tutorials on youtube.

###Problem 2: lexical Analysis ###
It was so difficult to obtain the output in the same range of token but then revising the lecture of sir i found out that it tokennizes the code one by one and create the token stream.

##References##
[links](https://github.com/starbops/MJP)
