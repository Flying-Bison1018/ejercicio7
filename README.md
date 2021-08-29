# ejercicio7
actividad
package ejercicio.pkg7;

/**
 *
 * @author PC
 */
import java.util.Scanner;
public class Ejercicio7 {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner entr = new Scanner(System.in);
        double preciodecompra;
        double preciodeventa;
        double resta;
        double x,i,j;
        int y=-1;
        int z = 100;
        double utilidad;
        
        
        System.out.print("Ingrese precio de ventas\n");
        preciodeventa = entr.nextDouble();
        System.out.print("Ingrese precio de compra\n");
        preciodecompra = entr.nextDouble();
        
        resta = preciodecompra-preciodeventa;
        i = resta;
        x = i/preciodeventa;
        j = x*y;
        utilidad = (j*z);
        
        System.out.printf("El porcentaje de utilidad es:"+utilidad);
        
        // TODO code application logic here
    }
    
}
