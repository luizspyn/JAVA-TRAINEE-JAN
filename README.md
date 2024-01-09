# JAVA-TRAINEE-JAN  

This code is a program that reads an integer N from the keyboard and prints on the screen whether it is "Weird" or "Not Weird", according to the following rules:

If N is odd, it is "Weird".
If N is even and is between 2 and 5 (inclusive), it is "Not Weird".
If N is even and is between 6 and 20 (inclusive), it is "Weird".
If N is even and greater than 20, it is "Not Weird".
To do this, the code uses the following classes and methods:

The class java.io.* is used to import the classes related to data input and output, such as System.in and System.out.
The class java.math.* is used to import the classes related to mathematics, such as BigInteger and BigDecimal.
The class java.security.* is used to import the classes related to security, such as SecureRandom and MessageDigest.
The class java.text.* is used to import the classes related to text formatting, such as DecimalFormat and SimpleDateFormat.
The class java.util.* is used to import the classes related to utilities, such as Scanner, Random and ArrayList.
The class java.util.concurrent.* is used to import the classes related to concurrency, such as ExecutorService and Future.
The class java.util.regex.* is used to import the classes related to regular expressions, such as Pattern and Matcher.
The class Solution is the main class of the program, which contains the main method.
The main method is the entry point of the program, which receives an array of strings as an argument, called args.
The variable scanner is an instance of the Scanner class, which is used to read data from the keyboard (System.in).
The nextInt method is used to read an integer from the keyboard and assign it to the variable N.
The skip method is used to ignore the special characters that may come after the number, such as line breaks or spaces.
The operator % is used to calculate the remainder of the division of N by 2, which is used to check if N is even or odd.
The operator || is used to perform a logical OR operation, which returns true if at least one of the conditions is true.
The operator && is used to perform a logical AND operation, which returns true if both conditions are true.
The operator >= is used to perform a comparison of greater than or equal, which returns true if the first value is greater than or equal to the second.
The operator <= is used to perform a comparison of less than or equal, which returns true if the first value is less than or equal to the second.
The if-else structure is used to execute a block of code if a condition is true, and another block of code if the condition is false.
The println method is used to print a message on the screen, followed by a line break.
The close method is used to close the scanner and release the associated resources.
