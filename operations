import java.util.Scanner;

public class operations{
     // Instance variables
    private int num1;
    private int num2;
    private int num3;

     // Constructor to initialize the variables
    public Operations(int num1, int num2, num3) {
        this.num1 = num1;
        this.num2 = num2;
        this.num3 = num3;
    }
        // Non-static method to display the instance variable
        public static int addNumbers(int num1, int num2, int num3){
            return num1 + num2 + num3;
        }
        // Static method to multiply two numbers
    public static int multiply(int a, int b) {
        return a * b;
    }

    // Static method to subtract two numbers
    public static int subtract(int a, int b) {
        return a - b;
    }
    public static void main(String[] args) {
         // Create an instance of the operations with numbers 1-10 and num 2-5

         Operations operations = new Operations(10, 5);

        // Call the non-static method on the object
        int additionResult = operations.add();
        System.out.println("Addition Result (num1 + num2): " + additionResult);

        // Call the static methods directly using the class name
        int multiplicationResult = Operations.multiply(3, 4);
        System.out.println("Multiplication Result (3 * 4): " + multiplicationResult);

        int subtractionResult = Operations.subtract(10, 5);
        System.out.println("Subtraction Result (10 - 5): " + subtractionResult);
    }       

}
