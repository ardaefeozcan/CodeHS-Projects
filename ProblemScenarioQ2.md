# ProblemScenarioQ2

The program asks the user to enter the number of ice creams sold for Chocolate, Vanilla, and Strawberry for three days. It calculates the total sales and the average sales (decimal and integer using casting). The shop’s performance grade (no if-else).

    import java.util.Scanner;
    
    
    public class MyProgram
    {
        public static void main(String[] args)
        {
            Scanner scanner = new Scanner(System.in);
                    
            System.out.println("Day 1 - Chocolate");
            int day1Chocolate = scanner.nextInt();
            
            System.out.println("Day 2 - Chocolate");
            int day2Chocolate = scanner.nextInt();
            
            System.out.println("Day 3 - Chocolate");
            int day3Chocolate = scanner.nextInt();
            
            System.out.println("Day 1 - Vanilla");
            int day1Vanilla = scanner.nextInt();
            
            System.out.println("Day 2 - Vanilla");
            int day2Vanilla = scanner.nextInt();
            
            System.out.println("Day 3 - Vanilla");
            int day3Vanilla = scanner.nextInt();
            
            System.out.println("Day 1 - Strawberry");
            int day1Strawberry = scanner.nextInt();
            
            System.out.println("Day 2 - Strawberry");
            int day2Strawberry = scanner.nextInt();
            
            System.out.println("Day 3 - Strawberry");
            int day3Strawberry = scanner.nextInt();
            
            int totalSalesChocolate = day1Chocolate + day2Chocolate + day3Chocolate;
            int totalSalesVanilla = day1Vanilla + day2Vanilla + day3Vanilla;
            int totalSalesStrawberry = day1Strawberry + day2Strawberry + day3Strawberry;
            int totalSales = totalSalesChocolate + totalSalesVanilla + totalSalesStrawberry;
            System.out.println("Total Sales Chocolate:" + totalSalesChocolate);
            System.out.println("Total Sales Vanilla:" + totalSalesVanilla);
            System.out.println("Total Sales Strawberry:" + totalSalesStrawberry);
            System.out.println("Total Sales :" + totalSales);
            double totalSalesDecimal = totalSales;
            System.out.println("Average(Decimal):" + totalSalesDecimal/9);
            System.out.println("Average(Integer):" + totalSales/9);
            System.out.println("Performance Grade: A");
    
    
    
    
        }
    }
