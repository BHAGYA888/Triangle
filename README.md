# Triangle
To print triangle

package triangle;

import java.util.Scanner;

public class Triangle {

    public static void main(String[] args) {
        // This prints an upper triangle
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the no. of Rows : ");
        int n = sc.nextInt();
        int i , j;
        for(i = 0 ; i<=n ; i++)
        {
            for(j=1 ; j <=n-i; j++)
            {
                System.out.print(" ");
            }
            for(j=1;j<=2*i-1;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
