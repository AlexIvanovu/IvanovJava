# IvanovJava

import java.util.Scanner;

public class Exercise1 {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        double referenceVariable = 7.0;
        System.out.println("Введите число: ");
        double variableBeingTested = scan.nextDouble();
        if (referenceVariable < variableBeingTested){
            System.out.println("Привет!");
        }

    }
}
