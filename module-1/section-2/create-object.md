# Basic way to create objects

As you’ve probably heard more than once, JavaScript is an extremely flexible language.

The syntax of the language allows us, in many cases, to achieve the same goal in different ways. It is no different with objects. There are several equivalent ways to create them, each with their own advantages and disadvantages. The simplest and most common is the use of literal notation – that is, the declaration presented earlier using curly brackets (another name for this is initializer notation).

In the example below, we create an empty object (without properties) and place it in the contact variable.

```bash 
  let contact = {};
```

We can modify an object created in this way by, among other things, adding new properties.

In our example, we add a property with the `tel ` key. Note that the property is indicated by writing its name after the object name, where the names are separated by a dot. This is called `dot notation`.

```bash 
contact.tel = "207-662-5412";

console.log(contact);
console.log(contact.tel);

```