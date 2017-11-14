1 
if the result is null, null could also be considered as an object
it can be avoided checking if bar is not null -----> if ((bar !== null) && (typeof bar === "object")); 


2 
in the outer funct THIS and SELF refer to myObject, in the inner fuction THIS does not refer to myObject anymore

outer func: this.foo = bar
outer func: self.foo = bar
inner func: this.foo = undfined
inner func:  self.foo = bar

3
To ensure that the content of the sript haqs closure, creating a namespace. 
Also could help avoiding issues between libraries


4
The arguments object is an object,
"object"


5
undefined
BAZ does not exists as a property of the object 


6 "1undefined"

fuctions work as booleans in JS
var x = 1; 
x += typeof f; 
x; 

f is not defined so adding an int (x) to a string equlas a string


7 white_rabbit
it was defined first as a constant

8 error
 the value was assign again before it was output


9 


10 in Prototypal Inheritance, instances inherit from other object, they may be made upo by several objects
in class inheritance , instances inherit from clases creating subclasses 

11
