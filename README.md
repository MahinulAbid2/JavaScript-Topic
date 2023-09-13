### Topic

<br>

* [Class overview](#class-overview)  
* [Object Prototype](#object-prototpye) 

<br>
<br>
<br>

# Class Overview

* Class is a `prototype` for an <ins>Object</ins>.
* What is `object prototype`?

<br>
<br>

```javascript
let StudentOne={
    firstName: "John",
    lastName:"Mark",
    age:20
}

let StudentTwo={
    firstName: "Kate",
    lastName:"William",
    age:23
}
let StudentThree={
    firstName: "Evelin",
    lastName:"Parker",
    age:24
}
let StudentFour={
    firstName: "Matthew",
    lastName:"Warner",
    age:25
}
let StudentFive={
    firstName: "Johnson",
    lastName:"Cillian",
    age:27
}
```

<br>
<br> 


#### Notice Something?

* These five object has `same structure` with <ins>Different Data</ins>.
* This code somehow looks `repetitive`.
* This is where `object prototype` comes.

<br>
<br> 

# Object Prototpye

<br>

* Object Prototype is an `object structure`.
* It will allow us to create many object with `different data`.
* This way it will take less code to write.

<br>

# Class Basic Syntax

```javascript
class ClassName{  // class name first letter must be Upperclass

    constructor(){
        // constructor is where I define the object structure
        // constructor is a method in class        
    }

    //we can also create CUSTOM method here.
}
```




