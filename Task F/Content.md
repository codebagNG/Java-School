# Arrays and Introduction to Data Structures
   
1. Declaring and Initializing an Array
  Array is a basic data structure in java, it is used to store a list of data that cannot change. Its declaration and initialization is shown below 
  
          int[] array1 = new int[4];//Array declared to have a length of 4
          array = {1,2,3,4};//Array initialized with the elements inside the curly bracket
          int[] newArray = {1,2,3,4};//Array declared and initialized

2. Multidimensional Array
   The array we created above is an array with single row and single column, but java provides for more flexibility in that we can have an arrays of multiple columns for each row, these arrays can be declared and initialized as shown below.
 
           int[][] array = new int[3][4];//This is a 3 by 4 array with 3 rows and 4 columns and can be visualized as a table.
           array[0] = {1,2,3,4};//This is initializing the first row of the array with the elements in the curly bracket. Using array[0] on a normal array will give you the first element of the array, so in the first array we created above array1[0] equals to 1. Note: Counting in most programming languages starts from 0 for the first element.
            array[0][0];// this will return the element in the first row and first column and this element is 1.

3. class Arrays
   Class Arrays is an inbuilt Java class that provides for more manipulations of an array. Before you can use the class Arrays you have to import it, you import it before the class declaration and it can be imported as shown below.
                 import java.utils.Arrays;
      After importing and declaring the classes and the methods needed you can now start using the class as shown below
                  Arrays.equals(array1,array2);//This checks if two arrays are equal
    Other methods of class Array will be explored in the tutorial classes.

 4. Collections is a compilation of data structures in java ranging from ArrayList to Maps to queues e.t.c. ArrayList is a mutable list that is a list that can change at runtime. Collections and ArrayList are best understood when used in practical applications and we will touch it briefly in our tutorial classes

 5. We will explore the card shuffling and dealing simulation as shown in the reference material we are using
           
