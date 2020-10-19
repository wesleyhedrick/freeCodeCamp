## Object-Oriented Programming

> As its name implies, object oriented programming organizes code into object definitions. These are sometimes called classes, and they group together data with related behavior. The data is an object's attributes, and the behavior (or functions) are methods.

> Objects can transfer information by calling and passing data to another object's methods. Also, new classes can receive, or inherit, all the features from a base or parent class. This helps to reduce repeated code.

## Constructors 

- functions that create new objects
    - functions
    - create new objects
    - Ex:  function Bird() {
                this.name = "Albert";
                this.color = "blue";
                this.numLegs = 2;
            }
    **Constructors are capitalized to distinguish them from other kinds of functions**

### How to Define (Create) a Constructor
    - function Bird() {
                    this.name = "Albert";
                    this.color = "blue";
                    this.numLegs = 2;
                }
### Make a Constructor Dynamic
    - function Bird(name, color) {
        this.name = name;
        this.color = color; 
        this.numLegs =2;
    }


### Create a new instance of a constructor
let parakeet = new Bird('Squawkins', 'Blue')

### instanceof
- use this to find out if an object is an instance of the original, ie. was created with teh constructor
- myHouse instance of House => returns true if

