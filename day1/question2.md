Blog about objects and its internal representation in javaScript:

Objects in JavaScript : 

    Objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs.
    These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.

What are the internal properties of objects in JavaScript?

    In JavaScript, objects have an internal property known as Prototype .
    The internal property [[Prototype]] points to the prototype of an object. It can be read via Object. getPrototypeOf(). ...
    The internal property [[Extensible]] determines whether or not one can add properties to an object. It can be read via Object. isExtensible().

What are the two types of objects in JavaScript?

    There are two types of object properties: The data property and the accessor property. 
    Each attribute is accessed internally by the JavaScript engine, but you can set them through Object.defineProperty() , or read them through Object.getOwnPropertyDescriptor() .

In JavaScript, almost "everything" is an object.

Booleans can be objects (if defined with the new keyword)
Numbers can be objects (if defined with the new keyword)
Strings can be objects (if defined with the new keyword)
Dates are always objects
Maths are always objects
Regular expressions are always objects
Arrays are always objects
Functions are always objects
Objects are always objects
All JavaScript values, except primitives, are objects.

Example:

Every object has some property associated with some value. These values can be accessed using these properties associated with them.
var myCar = new Object();
myCar.make = 'Suzuki';
myCar.model = 'Altros';
myCar.year = 1978;
myCar.wheels = 2;
After creating myCar object, the value inside the object can be accessed using keys.
i.e.
myCar.year
Output: 1978




