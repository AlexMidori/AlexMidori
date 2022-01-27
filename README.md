package md.curs.cursjava.lesson5;

import java.util.Scanner;
test
public class MethodsClass {
    public static void main(String[] args) {            
            
            Integer a = 0;
            Integer b = 0;
            char operatia;
            double raspuns=0;

            Scanner scanNumar = new Scanner(System.in);
        System.out.println("Adauga primul numar: ");
        a = scanNumar.nextInt();
        System.out.println("Adauga a doilea numar: ");
        b = scanNumar.nextInt();
        System.out.println("Adauga operatia: ");
        operatia = scanNumar.next().charAt(0);

        switch (operatia){
            case '+': raspuns = a + b;
            break;
            case '-': raspuns = a - b;
            break;
            case '*': raspuns = a * b;
            break;
            case '/': raspuns = a / b;
            break;
        }
        System.out.println(a+" "+operatia+ " "+b+" = "+raspuns);

        }
    }
