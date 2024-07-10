    import java.util.Scanner;
      
      public class Area{
        public static void main(String args[]){
        
        Scanner pp = new Scanner(System.in);
        System.out.println("Enter the radius of the Circle");
        int m = pp.nextInt();
        System.out.println("Well, the radius of your circle is: " + m);
        
        double Area;
        float p = 3.14f;
        int a = (m*m);
         Area = p*a;
         Area = Math.round (Area*10.0)/10.0;
         
         System.out.println("The area of the circle is: "+ Area);
        }
      }
      
 A-simple-Area-program
 This program will accept user input as the radius, compute the area of the circle and output the area in 1 decimal place.
