# Ejercicio_2

public class Main {


    public static void main(String[] args) {


//Ejercicio 1

        var numerolf = -3;

        if (numerolf == 0) {
            System.out.println("Es el numero 0.");
        } else if (numerolf < 0) {
            System.out.println("El numero es negativo.");
        } else {
            System.out.println("El numero es positivo.");
        }


//Ejercicio 2

        var numeroWhile = 1;

        while (numeroWhile <= 3) {
            System.out.println(numeroWhile);
            numeroWhile = numeroWhile + 1;
        }

//Ejercicio 3

        int nun = 3;

        do {
            System.out.println(nun);
            nun = nun + 1;
        }while (nun > 4);


//Ejercicio 4

        for (int numeroFor = 0; numeroFor <= 3; ++numeroFor){
                System.out.println(numeroFor);
        }

        
//Ejercicio 5

        var estacion = "perro";

        switch (estacion) {
            case "primavera":
                System.out.println("Estamos en primavera.");
                break;
            case "verano":
                System.out.println("Estamos en verano.");
                break;
            case "otoño":
                System.out.println("Estamos en otoño.");
                break;
            case "invierno":
                System.out.println("Estamos en invierno.");
                break;
            default:
                System.out.println("Tu respuesta no es una estacion.");
        }
    }
}
