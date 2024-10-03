java cHomework2
Note: Submit your work (upload the .java source code files ONLY, not the compiled .class files!) through the “Homework2” link on Brightspace. You may submit an unlimited number of times; we will only grade the last/latest submission attempt, but be sure to attach all of your files to each submission attempt. Be sure to include your name and Stony Brook ID number in a comment at the beginning of each file that you submit.
Due: Thursday, October 10, 11:59pm Total: 25 points (5 points per problem)
Submission Instructions: Name your java classes for this assignment as:
Problem1: Pyramid.java
Problem2: Interests.java
Problem3: LongestCommonPrefix.java Problem4: PerfectNumber.java Problem5: ArmstrongNumbers.java
1. Pyramid.java: (Printing numbers in a pyramid pattern) Write down a program in Java with a nested for loop that prints the following output (powers of 2) for any number of lines:
Here is a sample run:
Enter the number of lines: 8 Output:
1
121 12421 1248421
1 2 4 8 16 8 4 2 1
1 2 4 8 16 32 16 8 4 2 1
12 4 816326432168 4 2 1 124 81632641286432168 4 2 1
2. Interests.java: (Financial application: comparing loans with various interest rates) Write a program that lets the user enter the double loan amount and loan period in number of years (int) and displays the monthly and total payments for each interest rate starting from 5% to 8%, with an increment of 1/8.
   Here is the sample run:
Loan amount: 10000.00
Number of years: 5
Interest Rate Monthly Payment 5.000% 188.71
Total Payment
11322.74

5.125% 189.28 5.250% 189.85 ...
7.875% 202.16 8.000% 202.76
11357.13 11391.59
12129.97 12165.83
𝑑𝑜𝑢𝑏𝑙𝑒 𝑚𝑜𝑛𝑡h𝑙𝑦𝐼𝑛𝑡𝑒𝑟𝑒𝑠𝑡𝑅𝑎𝑡𝑒 = 𝑎𝑛𝑛𝑢𝑎𝑙𝐼𝑛𝑡𝑒𝑟𝑒𝑠𝑡𝑅𝑎𝑡𝑒 / 1200 ;
𝑑𝑜𝑢𝑏𝑙𝑒 𝑚𝑜𝑛𝑡h𝑙𝑦𝑃𝑎𝑦𝑚𝑒𝑛𝑡 = 𝑙𝑜𝑎𝑛𝐴𝑚𝑜𝑢𝑛𝑡 ∗ 𝑚𝑜𝑛𝑡h𝑙𝑦𝐼𝑛𝑡𝑒𝑟𝑒𝑠𝑡𝑅𝑎𝑡𝑒 / (1 − (𝑀𝑎𝑡h.𝑝𝑜𝑤(1/(1 + 𝑚𝑜𝑛𝑡h𝑙𝑦𝐼𝑛𝑡𝑒𝑟𝑒𝑠𝑡𝑅𝑎𝑡𝑒),𝑛𝑢𝑚𝑏𝑒𝑟𝑂𝑓𝑌𝑒𝑎𝑟𝑠 ∗ 12))); 𝑑𝑜𝑢𝑏𝑙𝑒 𝑡𝑜𝑡𝑎𝑙𝑃𝑎𝑦𝑚𝑒𝑛𝑡 = 𝑚𝑜𝑛𝑡h𝑙𝑦𝑃𝑎𝑦𝑚𝑒𝑛𝑡 ∗ 𝑛𝑢𝑚𝑏𝑒𝑟𝑂𝑓𝑌𝑒𝑎𝑟𝑠 ∗ 12; 𝑆𝑦𝑠𝑡𝑒𝑚.𝑜𝑢𝑡.𝑝𝑟𝑖𝑛𝑡𝑓("%.3𝑓%% %.2𝑓 %.2𝑓\𝑛",𝑎𝑛𝑛𝑢𝑎𝑙𝐼𝑛𝑡𝑒𝑟𝑒𝑠𝑡𝑅𝑎𝑡𝑒, 𝑚�代 写program、Java
代做程序编程语言�𝑛𝑡h𝑙𝑦𝐼𝑛𝑡𝑒𝑟𝑒𝑠𝑡𝑅𝑎𝑡𝑒, 𝑡𝑜𝑡𝑎𝑙𝑃𝑎𝑦𝑚𝑒𝑛𝑡);
3. LongestCommonPrefix.java: Write a program in Java that prompts the user to enter two strings and display the largest common prefix of the two strings. If there are no common prefix between the two entered strings display a message which tells the user that the two string doesn’t have a common prefix.
Here are some sample run:
Enter the first string: Atlanta
Enter the second string: Macon
Atlanta and Macon have no common prefix.
Enter the first string: Welcome to Java
Enter the second string: Welcome to programming
The common prefix is: Welcome to
Note: The prefix actually includes the space after ‘to’ as well
Enter the first string: I love coffee Enter the second string: I love Java The common prefix is I love
4. PerfectNumber.java: A positive integer is called a perfect number if it is equal to the sum of all of its positive divisors, excluding itself. For example, 6 is the first perfect number because 6 = 3 + 2 + 1. The next is 28 = 14 + 7 + 4 + 2 +1. Write a program that asks the user for an upper limit and prints all the perfect numbers up to that limit.
Here is a sample run:
Enter the upper limit: 10000
The perfect numbers below 10000 are: 6 28 496 8128.

5. ArmstrongNumbers.java: An Armstrong number is an n-digit integer such that the sum of the 𝑛𝑡h power of its digits is equal to the number itself. For example, 371 is an Armstrong number because 33 + 73 + 13 = 371 (371 is a 3-digit number). 8208 is an Armstrong number because 84 + 24 + 04 + 84 = 8208 (8208 is a 4-digit number). Write a program that asks the user for a lower limit and an upper limit and prints all the Armstrong numbers up to that limit.
Here are some sample runs:
Enter the lower limit: 10
Enter the upper limit: 1000
The Armstrong numbers between 10 and 1000 are: 153 370 371 407
Enter the lower limit: 8000
Enter the upper limit: 20000
The Armstrong numbers between 8000 and 20000 are: 8208 9474
Enter the lower limit: 25000
Enter the upper limit: 100000
The Armstrong numbers between 25000 and 100000 are: 54748 92727 93084

         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
