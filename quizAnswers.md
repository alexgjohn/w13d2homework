Polymorphism
What does the word 'polymorphism' mean?

>>Polymorphism means 'to have many forms'.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.

>>In OO design, this refers to the the same method being executed differently depending on which class is executing it. 

What can we use to implement polymorphism in Java?

>>We can use inheritance or interfaces to implement polymorphism in Java.

How many 'forms' can an object take when using polymorphism?

>>As far as I know, infinite!

Give an example of when you could use polymorphism.

>>A dog and a tortoise are both animals and both age. Therefore, they could both inherit from the parent class Animal, which can include an age() method. However, they would both age at different rates and would need to implement this method differently. 


Composition and Aggregation
What do we mean by 'composition' in reference to object-oriented programming?
>>IN OO, composition refers to a class being made up (or composed) of other classes.

When would you use composition? Provide a simple example in Java.
>>When a property of a class recurs and needs to have properties and methods of its own, it's appropriate to create this component class to have dry-er code. 

Give a difference between composition and aggregation?
>>Composition means one class being a part of another, contained within it. For example, a person has a stomach, so stomach is a component of person. Aggregation means one class containing ownership of one or more of another class. For example, a person may also have a bookshelf containing several books, so this would be an example of aggregation. 

What is/are the advantage(s) of using composition/aggregation?
>>Using composition/aggregation saves you from repetitive code for multiple classes that will share properties and methods in their functionality. 

When using composition, when an object is destroyed, what happens to all the objects it is composed of?
>>Those objects are also destroyed. 

When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
>>They're just fine! Except, of course, they no longer live inside whichever data structure was holding them in the destroyed object. 