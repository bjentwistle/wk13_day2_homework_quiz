# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
   -  the condition of occurring in several different forms.
     
3. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
  -   Polymorphism (computer science OOP), the ability in programming to present the same programming interface for differing underlying forms. In other words, when we talk of something being 'polymorphic' we mean that it can have 'many forms'. The beauty of "polymorphism" is that any type can behave as if it is any of it's super class types as well as it own.
  -   `public interface IChargeable { double charge(double amount);}`   This interface can be implemented in many classes of payment cards for example, which have different attributes and methods but can all use the interface function charge(amount).

4. What can we use to implement polymorphism in Java?
   - an interface class which is implemented into other classes. For example `public class Example implements Interface{}`

6. How many 'forms' can an object take when using polymorphism?
   - theorectically this can be infinite forms but there are limitations in codding when complexity is concerned. A class object can implement many forms of interface, as opposed to inheritance where the child object can only inherit from one Parent.

8. Give an example of when you could use polymorphism.



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

7. When would you use composition? Provide a simple example in Java.

8. Give a difference between composition and aggregation?

9. What is/are the advantage(s) of using composition/aggregation?

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
