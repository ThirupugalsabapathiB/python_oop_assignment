## Python OOP Assignment
Q1. What is the purpose of Python's OOP?

    Ans:object oriented programming is a programming paradigm that provides a means of structuring programs so that properties and behaviors are bundled into individual objects.

Q2. Where does an inheritance search look for an attribute?

    Ans: An inheritance search looks for an attribute first in the instance object, then in the class the instance was created from, then in all higher superclasses, progressing from left to right.

Q3. How do you distinguish between a class object and an instance object?

    Ans: A concrete thing that you constructed using a certain class is an object, which is an instance of a class. So, while the terms object and instance are interchangeable
    
        The term instance refers to an object's relationship to its class.

Q4. What makes the first argument in a class’s method function special?


Q5. What is the purpose of the init method?
    
    Ans:The __init__ is used to assigning the object within the class.

Q6. What is the process for creating a class instance?

    Ans:Creation of instance class is calling the class name and passing the objects when and where the class is called.

Q7. What is the process for creating a class?

    Ans:To create a class
            Enter class name
            constructor of a class
            method of a class

Q8. How would you define the superclasses of a class?

    Ans:super class is nothing but a parent class.super class is defined as the class from which the class inherits.


Q9. What is the relationship between classes and modules?

    Ans:A class is more of a unit,and a module is essentially a loose collection of stuff like functions,variables,or even classes.

Q10. How do you make instances and classes?

    Ans:create a class and call the class name and pass the variables and accepts the__init method.

Q11. Where and how should be class attributes created?

    Ans:class attributes is created directly in the class shared by all the objects in the class.
        

Q12. Where and how are instance attributes created?

    Ans:Instance attributes is created at the constructor of a class.

        def __init__(self,name,age)

Q13. What does the term "self" in a Python class mean?

    Ans:self means a reference made to the current object.

Q14. How does a Python class handle operator overloading?
      
    Ans:The operator overloading in Python means provide extended meaning beyond their predefined operational meaning. 

Q15. When do you consider allowing operator overloading of your classes?

    Ans:Ensures that objects of a class behave consistently with built-in types and other user-defined types.

Q16. What is the most popular form of operator overloading?

    Ans:The most frequent instance is the adding up operator +,where it can be used for the usual addition and also for combining two different strings.

Q17. What are the two most important concepts to grasp in order to comprehend Python OOP code?

    Ans:Inheritance and polymorphism are important concepts.

Q18. Describe three applications for exception processing?

    Ans:1.Exception is useful for dealing with errors cannot done in locally
        2.assign a control over to the exception and the error can be handled
        3.and the function throw the exception 

Q19. What happens if you don't do something extra to treat an exception?

    Ans:When an exception occurred, if you don't handle it, the program terminates abruptly and the code past the line that caused the exception will not get executed.

Q20. What are your options for recovering from an exception in your script?

    Ans:except handling can be used to eliminate the exception occured in try block in the script.

Q21. Describe two methods for triggering exceptions in your script?

    Ans:try
        Except

Q22. Identify two methods for specifying actions to be executed at termination time, regardless of  
whether or not an exception exists?

    Ans:Else and finally keywords.

Q23. What is the purpose of the try statement?

    Ans:The try statement allows you to define a block of code to be tested for errors while it is being executed.

Q24. What are the two most popular try statement variations?

Q25. What is the purpose of the raise statement?

    Ans:The raise keyword is used to raise an exception.You can define what kind of error to raise,and the text to print to the user.

Q26. What does the assert statement do, and what other statement is it like?

Q27. What is the purpose of the with/as argument, and what other statement is it like?

    Ans:The with statement replaces a try-catch block with a concise shorthand,It ensures closing resources right after processing them.

Q28. What are *args, **kwargs?

    Ans:args=Non-key valued type of arguments
        kwargs=key valued type of arguments

Q29. How can I pass optional or keyword parameters from one function to another?

    Ans:To pass optional or keyword parameters from one function to another,collect the arguments using the * and ** specifiers in the function's parameter list 

Q30. What are Lambda Functions?

Ans:Lambda functions ia an inline function,it is not user defined,we can create a very own function with the logical expression.

Q31. Explain Inheritance in Python with an example?

    Ans:Inheritance is the capability of one class to derive or inherit the properties of one class to another class.

    class person :
        def __init__(self,name):
        self.name=name

        def displayname(self):
        print(self.name)

    class employee(person):
        def is_employed(self):
        print(self.name, "is employed")

    emp=employee("xxx")
    emp.displayname()
    emp.is_employed()        

Q32. Suppose class C inherits from classes A and B as class C(A,B).Classes A and B both have their own versions of method func(). If we call func() from an object of 
class C, which version gets invoked?

    Ans:none gets invoked,class  c should have it's own  method of class 

Q33. Which methods/functions do we use to determine the type of instance and inheritance?

Q34.Explain the use of the 'nonlocal' keyword in Python.

    Ans:The nonlocal keyword is used to work with variables inside nested functions,where the variable should not belong to the inner function.

Q35. What is the global keyword?

    Ans:Global keyword is used to modify the global variable outside its current scope and meaning.
