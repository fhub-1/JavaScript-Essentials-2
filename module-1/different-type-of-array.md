# An object as a different type of array

From a formal point of view, an object can be treated as a special kind of array.

In computer science, arrays of this type are called association arrays (or, in the theory of data structures, they are called maps).

How do they differ from ordinary arrays? We don’t refer to the individual elements of an object by means of indexes, which define their position in the collection, but by means of keys (i.e. we "associate" an element with a key).

A key is simply a label (a name), which is unique within an object and unambiguously defines the selected element.

In objects, we call their component elements properties. Each property will consist of a key (or label) and a value.

The idea of objects comes from observing the surrounding reality. Practically everything in our environment, whether material (e.g. a car) or abstract (e.g. a contact in an address book) is a collection of certain components.

We can name these elements, or properties, and assign them specific values. Properties define a given object.


As we’ll see later in the course, JavaScript allows you to create objects in many different ways. The easiest way is to use curly brackets.
```bash
let sampleObject = {
    id: 10, 
    delay: 20,
    name: "en to tre",
    isPresent: true,
    delay: 50
};

sampleObject.delay = sampleObject.delay * 2;
console.log(sampleObject.id);   // -> 10
console.log(sampleObject.name); // -> en to tre
console.log(sampleObject.delay);    // -> 100
```

In the example, we have created a sampleObject containing five properties, modified the contents of the delay property and referred to the id, name, and delay properties (displaying their values).