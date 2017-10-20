# Assignment

package start.print.pkg1;

import java.util.Scanner;


public class StartPrint1 {

    
    public static void main(String[] args) {
       
        int i,j,star;
        Scanner input=new Scanner(System.in);
        System.out.println("enter the value");
        star=input.nextInt();
        for(i=1;i<=6;i++)
        {
            System.out.print("*");
        }
        
        System.out.println("*");
    }
    
    
}
