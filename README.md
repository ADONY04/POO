# POO
Tarea
Crear el código que imprima la siguiente salida: "Hola, soy Arnol Gutiérrez" (Usar su nombre) 
public class Hola{ 
    public static void main(String[] args) { 
        System.out.println( 
            "Hola soy Adony Majano "   
           ); 
    } 
}   
Crear un programa que imprima en consola todas las operaciones aritméticas de dos números enteros (suma, resta, multiplicación, divición, mod) public class 
 OperacionesAritmeticas{ 
 public static void main(String[] args){ 
  int a      = 20; 
  int b     = 15; 
  int suma   = a + b; 
  int resta  = a - b; 
  int mult   = a * b; 
  int div    = a / b; 
  int modulo = a % b; 
   
  System.out.print("Suma :"); 
  System.out.println(suma ); 
  System.out.print("Resta :"); 
  System.out.println(resta); 
  System.out.print("Multiplicacion :"); 
  System.out.println(mult); 
  System.out.print("Division :"); 
  System.out.println(div); 
  System.out.print("Modulo :"); 
  System.out.println(modulo);  
 } 
} 
Dadas las variables de tipo int M = 6, T = 1, K = -10 indicar si la evaluación de estas expresiones daría como resultado verdadero o falso: 
public class Condiciones {  
 public static void main(String args[]) { 
     int M = 6; 
        int T = 1; 
   if (M > T) { 
            System.out.println("VERDADERO"); 
        } else { 
            System.out.println("FALSO"); 
        } 
    } 
} 
   
 
Crear un arrelo que guarde e imprima 10 nombres de tus compañeros de la clase 
public class ArregloGrupos { 
    public static void main(String args[]) { 
        String[]  nombre = new String[10]; 
        nombre[0] = "YonI "; 
         nombre[1] = "Cecia "; 
         nombre[2] = "Gilberto "; 
         nombre[3] = "Ariel ";    
        nombre[4] = "Mauricio "; 
          nombre[5] = "Brayam "; 
          nombre[6] = "Luis"; 
            nombre[7] = "Elizabeth "; 
             nombre[8] = "Siloe "; 
              nombre[9] = "Daniela ";  
        System.out.println( 
            "los nombres son: " 
            + nombre[0] +  
         nombre[1]+   
         nombre[2]+  
         nombre[3]+   
          nombre[4]+   
          nombre[5]+   
          nombre[6]+   
            nombre[7]+   
             nombre[8] +  
              nombre[9] 
        );  
    }  
}  
Crear un arreglo multidimensional que guarde más datos personales tus compañeros de clase (nombre, apellido, carrera, lugarTrabajo), tomando como referencia de la información colocada en el foro Conociendonos. Llenar 5 registros  
public class ArregloGrupos { 
    public static void main(String args[]) { 
        String[] nombre = new String[5]; 
         String[] apellido = new String[5]; 
          String[] carrera= new String[5]; 
       
       nombre[0] = "Alberto"; 
       apellido[0] = "oliva"; 
       carrera[0] = "electronica";      
       nombre[1] = "Gilberto"; 
       apellido[1] = "Caceres"; 
        carrera[1] = "electronica"; 
       
       nombre[2] = "Luis"; 
        apellido[2] = "coto"; 
        carrera[2] = "industrial"; 
         
       nombre[3] = "German";   
       apellido[3] = "Duran"; 
       carrera[3] = "Computacion"; 
                 
        nombre[4] = "Saul";   
        apellido[4] = "Moreno"; 
       carrera[4] = "Electronico"; 
         
        System.out.println( 
            "el nombre es: " 
            +  nombre[0]  
             );            
          System.out.println( 
            "el apellido es: " 
            +  apellido[0]        
        ); 
         System.out.println( 
            "la carrera es: " 
            +  carrera[0]  
                           
       );  
    } 
} 

Crear el código en Java para: 
 Crear una clase que se llame Operaciones, con 5 métodos diferentes. 
 Instanciar la clase en el programa principal y llamar a los métodos con diferentes 
operaciones: 
El método debe retornar los siguientes tipos de valor:  
Primer método: Retornar un mensaje que diga: "Soy el mejor programador". 
Segundo método: Retornar un mensaje dependiendo de un parámetro de entrada entero 
de nota, si es mayor o igual a 70, el mensaje debe decir Aprobado, de lo contrario 
Reprobado. 
Tercer método: Retornar el resultado de una suma de dos enteros que proporcionemos 
como parámetros:   
Cuarto método:  Debe retornar una lista de números del 1 al X. Donde X es un parámetro 
de entrada del método a crear. 
Quinto método: debe retornar la resta y multiplicación de tres números con decímeles 
proporcionados como parámetros de entrada.        
public double calcularPromedio(double val1, double val2, 
                              double val3) { 
     
} 
public class Operaciones{ 
     
    public void operacion(String s) { 
         
    } 
    public void operacion(int i) { 
         
    } 
    public void operacion(double f) { 
        
    } 
    public void operacion(int i, double f) { 
         
    } 
}  
public class Program {  
public static void main(String arg[ ]) {  
    
Mensajes mensajes = new Mensajes();  
mensajes.parametro1();                  
mensajes.parametro2(10); 
mensajes.parametro3(10); 
mensajes.parametro4(10); 
mensajes.parametro5(10); 
    } 
    
    public static class Mensajes {  
   
  public void Saludo() { 
    System.out.println("Soy el Mejor Programador"); 
}  
public void dibujar(int edad) { 
  if (nota >= 70){ 
     System.out.println("Aprobado"); 
  }else{ 
     System.out.println("Reprobado"); 
     } 
    } 
   } 
  } 
  
  Creé una clase abstracta llamada Calculadora, que contenga los siguientes métodos abstractos, aplicando los conceptos de POO: 
   Fabricante.  
   Tamaño. 
   Color. 
   Modelo. 
public class Calculadora { 
     public static void main(String arg[]) { 
         Fabricante F= new Fabricante(); 
         System.out.println(F.getFacultad()); 
          Tamaño T = new Tamaño(); 
          System.out.println(T.getFacultad()); 
          Color C = new Color(); 
          System.out.println(C.getFacultad()); 
           Modelo M = new Modelo(); 
          System.out.println(M.getFacultad()); 
} 
ublic static abstract class  Calculador {    
    abstract String getFacultad(); 
    } 
    public static class Fabricante extends Calculador {    
    public String getFacultad() { 
            return "Fabricante"; 
        } 
    } 
     public static class Tamaño extends Calculador {     
         public String getFacultad() { 
            return "Tamaño"; 
        } 
    } 
    public static class Color extends Calculador {    
    public String getFacultad() { 
            return "Color"; 
        } 
    } 
    public static class Modelo extends Calculador {      
    public String getFacultad() { 
            return "Modelo"; 
        } 
    } 
2. Declare 3 clases con diferentes fabricantes extendiendo de la clase Computadora, por ejemplo:  
   CASIO 
public class Computadora { 
    public static void main(String[] args) { 
Fabricante e = new Fabricante( 
            "APPLE" 
        ); 
System.out.println(e.marca); 
 System.out.println(e.fabricante); 
    } 
 public static class Computadora { 
public String marca; 
private String fabricante; 
      public Computadora(String marca, String fabricante) { 
this.marca = marca; 
            this.fabricante = fabricante; 
        } 
        public void imprimirfabricante() { 
            System.out.println(fabricante); 
        } 
    } 
}  
Creando cada una de las instancias con sus respectivos atributos (Características de las marcas de calculadoras). 
3. Imprima cada marca de Fabricante con sus diferentes características 
4. Sean creativos y apliquen el concepto de modularidad en el presente ejercicio.  
public class Calculadora { 
    public static void main(String[] args) { 
        atributos a = new atributos( 
            "APPLE" 
        ); 
        System.out.println(e.fabricante); 
        System.out.println(e.tamaño); 
        System.out.println(e.color); 
        System.out.println(e.modelo); 
    } 
    public static class calculadora { 
        public String tamaño; 
        public String color; 
        public String modelo;  
 
        private String fabricante; 
        public calculadora(String marca, String atributos) { 
            this.tamaño = tamaño;         
             this.color = color;      
              this.modelo = modelo; 
            this.fabricante = fabricante; 
        } 
        public void imprimirfabricante() { 
            System.out.println(fabricante); 
        } 
    } 
} 

