# What I learned Week-10

This week we started learning about Objects and getting into JSON files.

---

## Objects.

- Objects are a collection of properties with associations between names and values. They're a nice way of organizing data into a more human readable form.

- The properties of an object define characteristics of the object. You can access these properties using dot notation like so:
  
  **obj.propertyName**

  - Remember to use commas after making each property in a object, this is common to forget when making objects.

Here is an object example:

const me = {
    firstName: 'Dallas',
    lastName: 'Clarke',
    age: 29
}

- Objects are mutable, like for example to change my firstName above you would do the following:

me.firstName = 'new name';

**Note**
- Object.assign can be used if not looking to mutate your object. It copies the values of the properties from one or more source objects to a target object.

---

## JSON

What is JSON?

- JavaScript Object Notation, used for storing and exchanging data and is written using JS object notation.

- JSON.stringify() is a commonly used when sending data back to/from a server. When sending this data it has to be a string. So you would use .stringify() to do that.
- JSON.parse() takes data from server and will convert it into a JS object.

