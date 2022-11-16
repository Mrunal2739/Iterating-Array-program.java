# Iterating-Array-program.java

import java.util.Arrays;

public class IteratingArray {

   public static void main(String args[]) {
   
      //Creating an array
      
      int myArray[] = new int[7];
      
      myArray[0] = 200;
      
      myArray[1] = 300;
      
      myArray[2] = 400;
      
      myArray[3] = 500;
      
      myArray[4] = 600;
      
      myArray[5] = 700;
      
      myArray[6] = 800;
      
      //Printing Contents using for each loop
      
      System.out.println("Contents of the array: ");
      
      for (int element: myArray) {
      
         System.out.println(element);
         
      }
      
   }
   
}
