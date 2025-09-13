#If and Else statements in java 
This java program explains if and else statement in java
```java
import java.util.Scanner;

class if_else   // Here the class should be file name ie: class file_name
{
    public static void main(String[]args)
{
    Scanner sc = new Scanner (System.in);

    int m_1,m_2,tot;
    float avg;
    String gr="";
    System.out.print("Enter marks of java: ");
    m_1 = sc.nextInt();
    System.out.print("Enter marks of SQL:");
    m_2 = sc.nextInt();
    tot=m_1+m_2;
    avg = (float)tot/2;
    if (avg >= 70) {
    gr = "A";
} else if (avg >= 40 && avg < 70) {
    gr = "B";
} else {
    gr = "C";
}
System.out.println("Total marks: " + tot);
System.out.println("Average marks: " + avg);
System.out.println("Grade:" + gr);
}
}
