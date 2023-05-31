# Digit-count-

Digit count

import java.util.*;

class digitCount{

    static int Count(int n){

        int count=0;

        while (n>0){

            n=n/10;

            count++;

        }

        return count;

    }

    public static void main(String... args){

        System.out.println("Enter the value of n: ");

        Scanner sc=new Scanner(System.in);

        int f=sc.nextInt();

        System.out.println("The number of digits in the given number is : "+ Count(f));

    }

}

/*

23322

The number of digits in the given number is : 5

 *
