import java.util.Scanner;

public class Main {


    public static void main(String args []) {
        System.out.println("Hello world !");
        int saving ;
        int interest=0.15;
       // syntax:variable x=( bol expression)? value if true :value if false;
        boolean twentyfivepercentsaving=true;
        boolean sixmonthsaving=true ;
        boolean togetloan= (twentyfivepercentsaving && sixmonthsaving );
        String name  = "client";
        System.out.println(name);
        System.out.println(togetloan);
      Scanner scan= new Scanner(System.in);
              String [] question =new String [6];
        System.out.println("what is your name?");
        question [0] = scan.nextLine();
        System.out.println("how much do you have?");
        question [1] = scan.nextLine();
        System.out.println("how much do you need?");
        question [2] = scan.nextLine();
        System.out.println("how many months did you save?");
        question [3] = scan.nextLine();
        System.out.println("in how many years did you plan to pay us back?");
        question [4] = scan.nextLine();
        System.out.println("do you have criminal record?");
        question [5] = scan.nextLine();
              

    }


}

