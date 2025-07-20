# [Video Link](https://youtu.be/TAtrPoaJ7gc)

## Write Java programs for the following:

1. Write a program to print whether a number is even or odd, also take
input from the user.
2. Take name as input and print a greeting message for that particular name.
3. Write a program to input principal, time, and rate (P, T, R) from the user and
find Simple Interest.
4. Take in two numbers and an operator (+, -, *, /) and calculate the value.
(Use if conditions)
5. Take 2 numbers as input and print the largest number.
6. Input currency in rupees and output in USD.
7. To calculate Fibonacci Series up to n numbers.
   Solution:
   ```
   System.out.println("Input n such that the program prints nth number in fibonacci series: ");
   int n = s.nextInt();
   int a = 0;
   int b = 1;
   System.out.println(a);
   System.out.println(b);
   int fibo = 0;
   for(int i=2; i<=n;i++){
     fibo = a+b;
     System.out.println(fibo);
     a = b;
     b = fibo;
   }
   System.out.print("The number at " +n+ " index is:" +fibo);
   ```
9. To find out whether the given String is Palindrome or not.
    ```
    System.out.println("Enter a string to check if its a palindrome or not:");
    String palindrome = s.nextLine();
    int len = palindrome.length();
    int left = 0;
    int right = len-1;
    while (left <= right){
      if (palindrome.charAt(left) == palindrome.charAt(right)){
        left = left + 1;
        right = right - 1;
      } else{
        System.out.println("Not palindrome");
        break;
      }
    }
    System.out.println("Palindrome");
    ```
11. To find Armstrong Number between two given number.
    ```
    System.out.println("Check whether a number is armstrong or not?");
    int n = s.nextInt();
    int sum = 0;
    while (n > 0){
      int digit = n % 10;
      System.out.println(digit);
      sum = sum + (int)Math.pow(digit,3);
      n = n/10;
    }
    System.out.println("Sum of all digits: " + sum);
    if ( sum == n){
      System.out.println("Number is armstrong number");
    } else{
      System.out.println("Number is not armstrong number");
    }
```

