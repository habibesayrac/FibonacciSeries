# FibonacciSeries

import java.util.Scanner;
public class Main {

    public static void main(String[] args) {

        int number1 = 0;
        int number2=1;
        int number3;
        System.out.println(number1);
        for (int i=1; i<10;i++) {

            number3 = number1 + number2;
            number1 = number2;
            number2 = number3;

            System.out.println(number1);
        }
            }
    }



