/* my first project
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package javaapplication22;

import java.util.Scanner;


/**
 *
 * @author KHALID AHMADI
 */
public class JavaApplication22 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner scanner = new Scanner(System.in);
      int a ;
      int b;
      String c ;
   
      System.out.print("enter first number: ");
      a= scanner.nextInt();
      System.out.print("enter the oprator:");
      c=scanner.nextLine();
      c=scanner.nextLine();
      System.out.print("enter the second number:");
      b=scanner.nextInt();
      switch(c){
        case"+":
            System.out.print(a+b);}
      switch(c){      
        case"-":
            System.out.print(a-b);}
      switch(c){
        case"*":
            System.out.print(a*b);}
      switch(c){
        case"/":
            System.out.print(a/b);
        scanner.close();
     }
      }
        
    }
    
