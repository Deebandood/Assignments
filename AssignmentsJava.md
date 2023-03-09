# Assignments
// Question : Take integer inputs till the user enters 0 and print the sum of all numbers (HINT: while loop)
import java.util.Scanner;
class workspace{
    public static void main(String[] args){
        Scanner input = new Scanner(System.in);
        int num= -1;
        int sum = 0;
        while(num !=0){
            System.out.println("Enter inputs");
            num = input.nextInt();
            sum = sum + num;
            System.out.println(sum);
        }

    }
}
