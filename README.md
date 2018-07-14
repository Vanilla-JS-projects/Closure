## The repo (as a part of an assignment) includes the information about what are 'closures' in javascript and how it basically works.



## **Closure**

It the combination of a function and the environment within which that
function was declared. Here, the enviornment means any local variables that were 
in scope at the time that the closure was created. Closure are the functions with preserved data.

Lexical Scoping defines how variable names are resolved in nested functions: inner functions contain the scope of parent functions even if the parent function has returned.


Closure defination/s in my words....


1) We know that local variables created inside the function are not accessible outside of it and are 
disposed by garbage collector after the function has returned or in other words, after it has finished the execution. But by defining a closure which is nothing but a function inside a function which uses lexical scope, we can have access to the variables of parent function at the global level. Such variables are also known as "Free Variables".


2) We can also use the variables defined at global level inside the function directly because of closure. Which means we do not need to pass any parameter while calling the function.

Eg.

let me = 'Akshil Shah'

function greet(){
	console.log('hello' + me + '!') //using "me" variable directly.
}

greet()  //not passing any arguments. 




References :

1) https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures
2) http://javascriptissexy.com/understand-javascript-closures-with-ease/
3) https://www.youtube.com/watch?v=CQqwU2Ixu-U
 
