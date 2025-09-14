# If_Else statements using alternative method of Switch case
Java program to perform if_else statements using switch case
```java
import java.util.*;  // * Can be used in place of Scanner
class main
{
   public static void main(String[]args)
{
    int num;
    String tx;
    Scanner sc= new Scanner(System.in);

    System.out.println("Enter any number between 1 and 3:");
    num=sc.nextInt();
    switch(num)  // switch case implementation
{
    case 1:
      tx="One";
      break;  //Using break here to avoid printing all output at once
    case 2:
      tx="Two";
      break;
    case 3:
      tx="Three";
      break;
    default:
      tx="Invalid number";
}
    System.out.println(tx);
}
}

   

