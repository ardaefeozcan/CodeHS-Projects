# ProblemScenerioQ4

Without using Math.sqrt, compute the square root of a number N using Newton’s method with three unrolled steps:
    x_(k+1) = 1/2 * ( x_k + N / x_k )
        Start with x0 = N/2.
        Compute x1, x2, and x3 manually (no loops, no if).
        Print the approximation in decimal and integer.


    import java.util.Scanner;
    
    public class manuelSQRT {
        public static void main(String[] args) {
            Scanner scanner = new Scanner(System.in);
    
            System.out.println("Enter N: ");
            double N = scanner.nextDouble();
    
            double guess0 = N / 2.0;
    
            double x1 = 0.5 * (x0 + N / x0);
            double x2 = 0.5 * (x1 + N / x1);
            double x3 = 0.5 * (x2 + N / x2);
    
            System.out.println("Initial guess x0 = " + x0);
            System.out.println("x1 = " + x1);
            System.out.println("x2 = " + x2);
            System.out.println("x3 = " + x3);
            System.out.println("Approx sqrt(N) ≈ " + x3);
            System.out.println("Approx sqrt(N) (int) = " + (int)x3);
        }
    }
