# ProblemScenerioQ3

A rocket is launched vertically from Earth.vThe user enters the rocket’s mass (kg), engine force (N), and burn time (s).The program calculates:Net acceleration = F / m, Final velocity = a * t, Altitude = 0.5 * a * t * t. Display both decimal and integer (cast) values.

    import java.util.Scanner;
    public class MyProgram
    {
        public static void main(String[] args)
        {
            Scanner scanner = new Scanner(System.in);
            
            System.out.print("Enter rocket mass (kg):");
            double mass = scanner.nextDouble();
            System.out.print("Enter engine force (N):");
            double engineForce = scanner.nextDouble();
            System.out.print("Enter burn time (s):");
            double burnTime = scanner.nextDouble();
            
            double netAccelaration = engineForce / mass;
            double finalVelocity = netAccelaration * burnTime;
            double altitude = 0.5 * netAccelaration * burnTime * burnTime;
            
            int netAccelarationI = (int) netAccelaration;
            int finalVelocityI = (int) finalVelocity;
            int altitudeI = (int) altitude;
            
            System.out.println("Net acceleration (m/s^2):" + netAccelaration);
            System.out.println("Net acceleration (int):" + netAccelarationI);
            System.out.println("Final velocity (m/s):" + finalVelocity);
            System.out.println("Final velocity (int):" + finalVelocityI);
            System.out.println("Altitude reached (m):" + altitude);
            System.out.println("Altitude (int):" + altitudeI);
            
        }
}
