import java.util.Scanner;
public class BasicCalculator {
    public static void main(String[] args) {
        while (true) {
            Scanner sc = new Scanner(System.in);
            System.out.println("Press '1' : Addition");
            System.out.println("Press '2' : Subtraction");
            System.out.println("Press '3' : Multiplication");
            System.out.println("Press '4' : Division");
            System.out.println("Press '5' : Exit");
            System.out.println("Enter option here");
            int option = sc.nextInt();
            options(option);
        }

    }

    public static void options (int option){
        switch (option) {
            case 1: {
                Scanner sc = new Scanner(System.in);
                System.out.println("Enter num1");
                double num1 = sc.nextDouble();
                System.out.println("Enter num2");
                double num2 = sc.nextDouble();
                System.out.println("Output is " + sum(num1, num2));
                break;
            }
            case 2: {
                Scanner sc = new Scanner(System.in);
                System.out.println("Enter num1");
                double num1 = sc.nextDouble();
                System.out.println("Enter num2");
                double num2 = sc.nextDouble();
                System.out.println("Output is " + sub(num1, num2));
                break;
            }
            case 3: {
                Scanner sc = new Scanner(System.in);
                System.out.println("Enter num1");
                double num1 = sc.nextDouble();
                System.out.println("Enter num2");
                double num2 = sc.nextDouble();
                System.out.println("Output is " + multiply(num1, num2));
                break;
            }
            case 4: {
                Scanner sc = new Scanner(System.in);
                System.out.println("Enter num1");
                double num1 = sc.nextDouble();
                System.out.println("Enter num2");
                double num2 = sc.nextDouble();
                System.out.println("Output is " + divide(num1, num2));
                break;
            }

            case 5:{
                System.exit(0);
            }
            default: {
                System.out.println("No option selected");
            }
        }
    }

    public static double sum ( double num1, double num2){
        return (num1 + num2);
    }

    public static double multiply ( double num1, double num2){
        return (num1 * num2);
    }

    public static double sub ( double num1, double num2){
        return (num1 - num2);
    }

    public static double divide ( double num1, double num2){
        return (num1 / num2);
    }
}
