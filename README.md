
22020820 




import java.util.Scanner;

public class Marks{
    public static void main (String [] args){

        System.out.println("         ACHIEVEMENT LEVELS      ");
        System.out.println("**********************************");

        Scanner input = new Scanner(System.in);

        System.out.println("Enter the marks of the student");
       int marks = input.nextInt();

        System.out.println("Student have achieved the following achievement: ");

        if(marks >= 80 && marks <= 100){
            System.out.println("Outstanding achievement");

        }
        else if(marks >=60  && marks <= 79){
            System.out.println("Meritorious achievement");    }
        else if(marks >=50  && marks <= 59){
            System.out.println("Satisfactory achievement");

        }
        else if(marks >=40  && marks <= 49){
            System.out.println("Adequate achievement");

        }
        else if(marks >=30  && marks <= 39){
            System.out.println("Partial achievement");

        }
        else{
            System.out.println("Inadequate achievement");

        }

    }
}
