Write a complete Java program in a class named Egg2 that generates the following output. Use static methods to show structure and eliminate redundancy in your solution.

  _______
 /       \
/         \
\         /
 \_______/
-"-'-"-'-"-
  _______
 /       \
/         \
\         /
 \_______/
-"-'-"-'-"-
\         /
 \_______/
  _______
 /       \
/         \
-"-'-"-'-"-
\         /
 \_______/
 
 
public class Egg2 {
    public static void main(String[]args) {

    Line1();Line2();Line3();Line4();Line5();Line6();
    Line1();Line2();Line3();Line4();Line5();Line6();
    Line4();
    Line5();
    Line1();Line2();Line3();Line6();Line4();Line5();
    }
    public static void Line1(){
    System.out.println("  _______");
    }
    public static void Line2(){
    System.out.println(" /       \\");
    }
    public static void Line3(){
    System.out.println("/         \\");
    }
    public static void Line4(){
    System.out.println("\\         /");
    }
    public static void Line5(){
    System.out.println(" \\_______/");
    }
    public static void Line6(){
    System.out.println("-\"-'-\"-'-\"-");
    }
}
