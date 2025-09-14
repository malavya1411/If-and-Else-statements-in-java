# Application of if_else statement in java
Using if_else statements in java to calculate grades of students
```java
import java.util.*;

class main
{
    public static void main(String[]args)
{
    Scanner sc = new Scanner(System.in);

    int m_1,m_2,m_3,tot;
    float p;
    System.out.print("Enter marks in java out of 100: ");
        m_1=sc.nextInt();
    System.out.print("Enter marks in SQL out of 100: ");
        m_2=sc.nextInt();
    System.out.print("Enter marks in CSS out of 100: ");
        m_3=sc.nextInt();    
    tot=m_1+m_2+m_3;
    p=((float)tot*100)/300;
    System.out.println("Percentage is :"+p);
    
    if (p<=100 && p>=95)
        System.out.println("Your Grade is : A+");
    else if (p<95 && p>=90)
        System.out.println("Your Grade is : A");
    else if (p<90 && p>=85)
        System.out.println("Your Grade is : B+");
    else if (p<85 && p>=80)
        System.out.println("Your Grade is : B");    
    else if (p<80 && p>=70)
        System.out.println("Your Grade is : C+");
    else if (p<70 && p>=60)
        System.out.println("Your Grade is : C");
    else if (p<60 && p>=50)
        System.out.println("Your Grade is : D");
    else if (p<50 && p>=40)
        System.out.println("Your Grade is : E");
    else 
    System.out.println("Fail");    
}  
}
