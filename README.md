# geekbrains_java1
package ru.geekbrains.firstlesson;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        //Целочисленный тип
        short s;
        int i;
        long l;

        //Плавающая запятая
        float f;
        double q;

        // Символьный тип
        char y;

        //Логический тип
        boolean bool = true;
        boolean bool2 = false;

        // Посчитай a* (b + (c / d))
        int a = 4;
        int b = 10;
        int c = 15;
        int d = 2;
        int w = a * (b + (c / d));
        System.out.println("a*(b + (c / d))=" + w);
        int v = 5;
        int k = 8;
        int o = v + k;
        while (true) {
            System.out.println("Сумма v+k  лежит в пределах от 10 до 20(включительно)?");
            if (o >= 10 && o <= 20) {
                System.out.println("Да!");
            } else {
                System.out.println("Нет!");
                break;
            }
            int n = 1;
            if (n >= 0) {
                System.out.println("Число положительное");
            } else if (n < 0) {
                System.out.println("Число отрицательное");
            }
            break;
        }
        while (true) {
            int h = -8;
            if (h < 0) {
                System.out.println("Число равно" + h);
            } else {

            }
            break;

        }
String p = " Вася";
        System.out.println("Привет"+ p);


            }

        }
