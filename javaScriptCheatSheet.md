#JavaScript Cheat Sheet

- array.push() - adds item to end of array
- array.unshift() - adds item to beginning of array
- array.pop() - removes last item in an array
    - Pop can also be used to return the last item from an array 
      Array = [1,2,3]
      lastNumber = array.pop()
        - 3
- array.shift() - removes item at beginning of array
    - shift() can also be used to return the last item from an array
- array.splice() - removes any number of elements starting at any point in an array.
    - Like pop and shift, it returns a new array
    - splice() can also insert elements

##Spread 
- makes a copy of an array without affecting the original array
    
##Cool Spread Applications
- copy array 
    - myArray = [1,2,3,4]
    - myNewArray = [...myArray]
    - Any changes made to either of the above arrays will not affect the other.
- insert one array into another
    - myArray = [1,2,3,8]
    - myNewArray = [4,5,6,7]
    - myArray = [1,2, ...myNewArray, 8]
        - Note: Don't use the brackets here

- indexOf()
    - returns -1 if no match is found
    - returns the index of the found object if the object is found


- Javascript Objects
    - At their most basic JS objects are key-value pairs
    - a piece of data(value) is paired with a unique identifier(key)
    - **Add to Objects in Two Ways**
        - bracket notation []
            - myObject['pears'] = 25
            - This adds a new key 'pears' and gives it the value of 25
            - advantage is it allows more flexibility in the key. 
        - dot notation .
            - myObject.pears = 25
            - This adds a new key 'pears' and gives it the value of 25
#Really Cool super-duper note
    **You can mix bracket and dot notation: obj[eyes].color**
    - **Delete Items**
        - delete myObject.pears
 
    - Check if a key exists in an object
        - obj.hasOwnProperty()
        - 'Alan' in obj
        - both of these **evaluate** to true if the key exists
    - Object.keys() 
        - quick and dirty way to generate an array of the object's keys
        - Object.keys(obj)
        


