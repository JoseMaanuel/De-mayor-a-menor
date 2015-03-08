# De-mayor-a-menor
package mayoramenor;

import java.util.*;
public class MayorAMenor {

    
    public static void main(String[] args) {
       Scanner lec=new Scanner(System.in);
       int A,B,C;
       
       System.out.println("Ingrese tres numeros");
        System.out.println("");
       System.out.println("Introduzca el primer numero");
       A=lec.nextInt();
       System.out.println("Introduzca el segundo numero");
       B=lec.nextInt();
       System.out.println("Introduzca el tercer numero");
       C=lec.nextInt();
       
       if(A>B&&A>C){
           System.out.println("El orden de mayor a menor es:");
           System.out.println(A);
           System.out.println(B);
           System.out.println(C);
       }else if(B>C){
           System.out.println("El orden de mayor a menor es:");
           System.out.println(A);
           System.out.println(C);
           System.out.println(B);
       }
       if(B>A&&B>C){
           System.out.println("El orden de mayor a menor es:");
           System.out.println(B);
           System.out.println(C);
           System.out.println(A);        
       }else if(A>C){
           System.out.println("El orden de mayor a menor es:");
           System.out.println(B);
           System.out.println(A);
           System.out.println(C);
       }
       if(C>A&&C>B){
           System.out.println("El orden de mayor a menor es:");
           System.out.println(C);
           System.out.println(B);
           System.out.println(A);
       }else if(A>B){
           System.out.println("El orden de mayor a menor es:");
           System.out.println(C);
           System.out.println(A);
           System.out.println(B);
       } 
    }
    
}
