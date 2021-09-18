# Difference between const, var and let

Variables are containers that store values. You start by declaring a variable.

  _There are 3 ways to declare a JavaScript variable:_
   - Using var
   - Using let
   - Using const

   **var** :
   Variables declared using var keyword scoped to the current execution context. This means if they are inside a function we only can access them inside the function and if they are not, they are part of the global scope which we can access anywhere. 

   One of the issues with using the var keyword is they can be redeclared inside the same scope. This will brings up some serious issues if we declare another variable using the same name inside the same scope, the new variable will replace the old one. var can be updated as well.

   **let** :
  This is the improved version of var declarations. Variables declaration using this way eliminates all the issues that we discussed earlier. let creates variables that are block-scoped. Also, they can not be redeclared and can be updated. 