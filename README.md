# Create-a-program-to-find-the-area-of-a-circle-java-
Create a program to find the area of a circle (java)

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package a;

import java.util.Scanner;

/**
 *
 * @author MI PC1
 */
public class A {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
    

         double radio, area;         
         System.out.println("Create a program to find the area of a circle (java)");
         System.out.print("Insertar el radio r = ");
         Scanner scanner = new Scanner(System.in);
         radio = scanner.nextFloat();
         area =  (3.14159*radio*radio);            
         System.out.println("Area = " + area);         
     }           
}

    
    

