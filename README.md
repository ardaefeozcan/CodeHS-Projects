# ProblemScenarioQ1

    import java.util.Scanner;

    public class MyProgram
    {

        public static void main(String[] args)
        {
            Scanner scanner = new Scanner(System.in);
            System.out.println("First Number:");
            double num1 = scanner.nextInt();
            System.out.println("Second Number:");
            double num2 = scanner.nextInt();
        
            double sum = num1 + num2;
        
            double diffrence = num1 - num2;
        
            double product = num1 * num2;
        
            double quotient = num1 / num2;
        

        
            System.out.println("First Number:" + num1);
            System.out.println("Second Number:" + num2);
            System.out.println("Sum" + sum);
            System.out.println("Diffrence:" + diffrence);
            System.out.println("Product:" + product);
            if (num2 == 0){
                System.out.print("Quotient: Undefined(Num2 can't be 0)");
            } else {
                System.out.println("Quotient:" + quotient);
            }
        }
    }
