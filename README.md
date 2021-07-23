# Tarea-2-Encriptador
package encriptador;

import java.util.Scanner;
/**
 *
 * @author Sarita Chinchilla
 */
public class Encriptador {

    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc = new Scanner(System.in);
        int primer = 'a';
        int ultimo = 'l';
 
        System.out.print("Introduce un caracter: ");
         char letra = sc.next().charAt(0);
         System.out.print("El caracter complementario es: ");
         int resultado = ultimo-letra;
         System.out.println((char)(primer+resultado));
    }
    
}
