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
* Each object has `same property` but it has different data value.
* There is a way to write less code and that is `class`.

<br>
<br> 


# Class Basic Syntax


```javascript
class ClassName{  // class name first letter must be Uppercase

    constructor(){
        // constructor is where I define the OBJECT STRUCTURE
        // constructor is a method in class        
    }

}
```

<br>

### Creating a new Class 

```javascript
class StudentForm {
    constructor (firstName, lastName, age) {
        this.firstName = firstName;
        this.lastName = lastName;
        this.age= age;
    }
}
```

<br>

* <ins>Explaination</ins>
* `constructor (firstName, lastName, age) {` - Hey Class, I will create a lot of object which will have these similar properties --- `firstName`, `lastName`, `age`.


