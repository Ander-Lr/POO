
package pkg11p1taller1laraanderson;

import java.util.Scanner;





public class Main {
    
    

    public static void main(String[] args) {
        
        Scanner scanner =new Scanner(System.in);
        
        System.out.println("UNIVERSIDAD DE LAS FUERAS ARMADAS ESPE");
        System.out.println("NOMBRE: ANDERSON LENIN LARA CHICAIZA");
        System.out.println("TALLER 1");
        System.out.println("POO");
        
        System.out.println("--------------------------------");
        System.out.println("OPERACIONES CON DOS NUMEROS");
        System.out.println("--------------------------------");
        System.out.println("INGRESE NUMERO 1: ");
        double num1=scanner.nextDouble();
        System.out.println("INGRESE NUMERO 2: ");
        double num2=scanner.nextDouble();
        
       double suma=num1+num2;
       double resta=num1-num2;
       double multiplicar=num1*num2;
       double division=num1/num2;
       
        System.out.println("LA SUMA DE NUMERO 1 Y NUMERO 2 ES: "+suma);
        System.out.println("LA resta DE NUMERO 1 Y NUMERO 2 ES: "+resta);
         System.out.println("LA multipicicon DE NUMERO 1 Y NUMERO 2 ES: "+multiplicar);
          System.out.println("LA multipicicon DE NUMERO 1 Y NUMERO 2 ES: "+division);
        
        
        
        
       
    }
    
}
