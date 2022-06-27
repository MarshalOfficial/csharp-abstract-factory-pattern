## C# Abstract Factory

The Abstract Factory design pattern provides an interface for creating families of related or dependent objects without specifying their concrete classes.

  

### Frequency of use: high  
  
    
### Participants:  
  The classes and objects participating in this pattern include:

- AbstractFactory  (ContinentFactory):  
declares an interface for operations that create abstract products
- ConcreteFactory   (AfricaFactory, AmericaFactory):  
implements the operations to create concrete product objects
- AbstractProduct   (Herbivore, Carnivore):  
declares an interface for a type of product object
- Product  (Wildebeest, Lion, Bison, Wolf):  
-- defines a product object to be created by the corresponding concrete factory  
-- implements the AbstractProduct interface
- Client (AnimalWorld):  
uses interfaces declared by AbstractFactory and AbstractProduct classes