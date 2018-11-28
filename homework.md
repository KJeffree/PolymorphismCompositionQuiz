# Polymorphism
What does the word 'polymorphism' mean?
- Something that can take many forms, for example a person can be a Software Developer, as well as a Rugby Fan, a Partner, a Parent, etc.
- The person will be the different type of themselves in different situations (e.g. they are not a parent when working on Software Development)

What does it mean when we apply polymorphism to OO design? Give a simple Java example.
- Being able to treat a class as if it is of another class
- A class can have multiple classes or types at once
- For example, athletes may have interfaces of IRun, ISwim and ICycle, where IRun can be used for a Runner, ISwim for a swimmer and ICycle for a cyclist, but all three for a triathlete

What can we use to implement polymorphism in Java?
- Interfaces

How many 'forms' can an object take when using polymorphism?
- Many, there is no limit to the number of forms an object can take.

Give an example of when you could use polymorphism.
- You could use polymorphism for a sound system that may connect different types of devices using IConnect. All the devices that have the IConnect interface will be able to connect to the sound system.

# Composition
What do we mean by 'composition' in reference to object-oriented programming?
- Something that HAS something rather than IS something (from inheritance)
- E.g. a house HAS a living room, a Kitchen and a Bedroom.

When would you use composition? Provide a simple example in Java.
- When classes that are inheriting from different parents are using the same methods, e.g. computer, printer, speaker may inherit from different abstract classes, but they all have the method outputData(), and so using composition here will allow all these classes to implement this method.

What is/are the advantage(s) of using composition?
- Don't get into a tangle with classes and overridden methods
- You can implement many interfaces, as apposed to just inheriting from one place

What happens to the behaviours when the object composed of them is destroyed?
- They are also destroyed
