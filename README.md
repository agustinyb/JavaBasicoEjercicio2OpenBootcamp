# JavaBasicoEjercicio2OpenBootcamp

import java.util.Scanner;

public class Main {

       public static void main(String[] args) {
                Scanner sc = new Scanner (System.in);
                precioIva();
            }
            public static void precioIva(){

                int precio = 8900;

                int resultado = precio + (precio /100) * 19;

                System.out.println("El total + el iva es igual a " + resultado);

       }
   }


