# Topic To cover
* class
* callback
* promises
* instiation
* 

<br>

### Topic

* [Class overview](#class-overview)  
* [Object Prototype](#object-prototpye) 

<br>
<br>
<br>

# Class Overview


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


### These five object has `same structure` with `Different Data`

```javascript
//with javascript class
//we can create same 5 object with 5 small LINE.

let StudentOne= new StudentForm("John","Mark",20);
let StudentTwo= new StudentForm("Kate","William",23);
let StudentThree= new StudentForm("Evelin","Parker",24);
let StudentFour= new StudentForm("Matthew","Warner",25;
let StudentFive= new StudentForm("Johnson","Cillian",27);
```

<br>
<br> 


# Class Basic Syntax

### class has different a little bit different syntax than an object.

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

//creating new Object From Class
let ObjectOne= new StudentForm("john","mark",30);
```

<br>

* <ins>Explaination</ins>

```javascript
constructor (firstName, lastName, age) {
//  Hey Class, I will create a lot of object which will have these similar properties --- `firstName`, `lastName`, `age`.
```





```javascript
this.firstName = firstName;
// hey class, if you have any "firstName" parameter in the the constructor function
// then assign this to the object property named = "firstName"
```


```javascript
//object structure
const ObjectName={
    Property_Name: Property_Value, // comma not semi-colon(;)
    Method_Name: ()=>{
        // regular function syntax

        let x=10;
        // here = not :  (equal not colon for assigning)
        // ; not ,        
    }
}
```

