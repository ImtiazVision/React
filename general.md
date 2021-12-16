### React 

**React** : is a framework for creating graphical user interfaces.

The Spread Operator literally distributes the contents of an array into its components, making operations like concatenation and so on easier. If we wish to concatenate two arrays, we may do it using the `concat` function, as seen below: 

```x = [1,2,3];
y = [4,5,6];
z = x.concat(y);
console.log("z: " + z);
```
Alternatively, we may use the Spread Operator to get the same result:

```
x = [1,2,3];
y = [4,5,6];
z = [...x, ...y]; //spread operator
console.log("z: " + z);

```

In React, we can use the Spread Operator to join two objects and add more attributes to that object. Let's assume we have two objects, obj1 and obj2, and we want to combine them to get a new one that has all of the features of both. Consider the following example:

```
const obj1 = { name: "Jhon"};
const obj2 = { ID: "21", GPA: "3.0"};

const obj3 = { ...obj1, ...obj2, semester: '3'};
console.log("The new object is : " , obj3);
```
