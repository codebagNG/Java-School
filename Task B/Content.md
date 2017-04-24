# Introduction to Classes, Objects and Objects
 
  In this Section we will be taking an Introduction to Classes, Objects and Methods. You can view a class as a blueprint of a car(design of a car), and we all know that a car's blueprint cannot move or convey anything unless the blueprint is converted into a real car, that is where the concept of object comes in, in which an object of a car is an instance of class, having all the abilities portrayed by the class. And then we have methods which can be viewed as the different mechanism of functioning of  a car in the car analogy, like the breaking mechanism, the gear mechanism e.t.c. So the method of a class, also has a representation in the classes's object as the design of a car's blueprint gear, braking mechanisms e.t.c has a real representation in the real life.

# Declaring and Instantiating a class with method
    
     Declaring a class

```
           //Book.java, 
           //Class declaration with one method.
           public class Book //A class declaration
           {
           // display a welcome message to the GradeBook user
             public void displayMessage()
            {
            System.out.println( "Welcome to the Grade Book!" );
                   } // end method displayMessage
                  } // end class Book
```
      Instantiating an object of a Class

``` 
            //BookTest.java
            // Creating a Book object and calling its displayMessage method.
            public class BookTest{ //Take Note of the name of the file name and the class name(note BookTest.java is the file name)
            // main method begins program execution
            public static void main( String[] args )
            {
            // create a Book object and assign it to myBook
            Book myBook = new Book();
            // call myBook's displayMessage method
            myBook.displayMessage();
            } // end
            } // end class BookTest
```

# Instance variables of a Class
    Instance variables can be viewed as the attributes the created object is going to have, like in the car analogy, the color of the car, the fuel tank e.t.c. Note that instance of class is the class's Object 




  Those are the basics of this section, for the other parts and more on the part we have discussed we are going to be using our reference material, the internet and the tutorial videos together.


        

