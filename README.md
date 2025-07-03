# name
public class Main {
    public static void main(String[] args) {
        String name = "Ridhima";
        int age = 23;
        String favoriteLanguage = "Java";

        System.out.println("My name is " + name + ", I am " + age + " years old, and my favorite programming language is " + favoriteLanguage + ".");
    }
}
#subject marks avg
public class Main {
    public static void main(String[] args) {
        int subject1 = 85;
        int subject2 = 90;
        int subject3 = 95;

        float average = (subject1 + subject2 + subject3) / 3.0f;

        System.out.println("Average marks: " + average);
    }
}
#sumdiffquet
public class Main {
    public static void main(String[] args) {
        int num1 = 20;
        int num2 = 5;

        int sum = num1 + num2;
        int difference = num1 - num2;
        int product = num1 * num2;
        int quotient = num1 / num2;

        System.out.println("Sum: " + sum);
        System.out.println("Difference: " + difference);
        System.out.println("Product: " + product);
        System.out.println("Quotient: " + quotient);
    }
}
#floattointeger
public class Main {
    public static void main(String[] args) {
        float floatValue = 9.75f;
        int intValue = (int) floatValue;

        System.out.println("Float value: " + floatValue);
        System.out.println("Converted to int: " + intValue);

        int intNum = 42;
        double doubleValue = (double) intNum;

        System.out.println("Integer value: " + intNum);
        System.out.println("Converted to double: " + doubleValue);
    }
}
#primitivedatatype
public class Main {
    public static void main(String[] args) {
        int myInt = 25;
        float myFloat = 3.14f;
        double myDouble = 123.456;
        char myChar = 'A';
        boolean myBoolean = true;

        System.out.println("int: " + myInt);
        System.out.println("float: " + myFloat);
        System.out.println("double: " + myDouble);
        System.out.println("char: " + myChar);
        System.out.println("boolean: " + myBoolean);
    }
}
#comparison 
public class Main {
    public static void main(String[] args) {
        int num1 = 25;
        int num2 = 30;

        if (num1 > num2) {
            System.out.println(num1 + " is greater");
        } else if (num2 > num1) {
            System.out.println(num2 + " is greater");
        } else {
            System.out.println("Both are equal");
        }
    }
}
#evenoddusingoperator
public class Main {
    public static void main(String[] args) {
        int number = 7;

        if (number % 2 == 0) {
            System.out.println(number + " is even");
        } else {
            System.out.println(number + " is odd");
        }
    }
}
#celtofar
public class Main {
    public static void main(String[] args) {
        double celsius = 25.0;
        double fahrenheit = (celsius * 9 / 5) + 32;

        System.out.println("Temperature in Celsius: " + celsius);
        System.out.println("Temperature in Fahrenheit: " + fahrenheit);
    }
}
#forloopprint1to10
public class Main {
    public static void main(String[] args) {
        for (int i = 1; i <= 10; i++) {
            System.out.println(i);
        }
    }
}
#sumfrom1ton
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int sum = 0;

        for (int i = 1; i <= n; i++) {
            sum += i;
        }

        System.out.println("Sum from 1 to " + n + " is: " + sum);
    }
}
#prime
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int num = sc.nextInt();
        boolean isPrime = true;

        if (num <= 1) {
            isPrime = false;
        } else {
            for (int i = 2; i <= num / 2; i++) {
                if (num % i == 0) {
                    isPrime = false;
                    break;
                }
            }
        }

        if (isPrime) {
            System.out.println(num + " is a prime number.");
        } else {
            System.out.println(num + " is not a prime number.");
        }
    }
}
#maxelement
public class Main {
    public static void main(String[] args) {
        int[] arr = {10, 25, 7, 30, 15};

        System.out.println("Array elements:");
        for (int i = 0; i < arr.length; i++) {
            System.out.println(arr[i]);
        }

        int max = arr[0];
        for (int i = 1; i < arr.length; i++) {
            if (arr[i] > max) {
                max = arr[i];
            }
        }

        System.out.println("Maximum element: " + max);
    }
}






