# My-Java-Codes-
This contain my java codes of projects I have been handling.

/*Using bufferd reader */


import java.io.*;
public class App {
    public static void main(String[] args) throws IOException {
        BufferedReader input =new BufferedReader (new InputStreamReader(System.in));
        String strnum1;String strnum2;
        int num1; int num2; int sum = 0;
        System.out.println("enter num 1 please: ");
        strnum1 = input.readLine();
        num1 = Integer.parseInt(strnum1);
        System.out.println("Enter num 2 please: ");
        strnum2 = input.readLine();
        num2 = Integer.parseInt(strnum2);
        sum = num1 + num2;
        System.out.println("sum ="+ sum);
        
    }
}







/*Scanner method */

import java.util.Scanner;
public class ScannerTest{
public static void main(String agrs[]) 
Scanner scanner = new Scanner(System.in) {
    System.out.println("Enter an interger:");
    int intValue = scanner.nextInt();
    System.out.println(("You enterd an interger ")+ intValue);
}
}



/*variable int */



public class DataTypes {
    public static void main (String[] agrs) {
        int age;
        int netWorth;
        int sum;
        netWorth = 500000000;
        age = 20;
        sum = age * netWorth;
        System.out.println("Goodmorning Milton, thanks for showing intrest in our company.");
        System.out.println("Your loan limit as per now is sh." +sum);
        
}     
}
    





/* Variable string */


public class DataTypes {
    public static void main (String[] agrs) {
        String name;
        name = "Milton";

        System.out.println("Hello "+ name+" Someone whants to talk to you");
        
    }      
    }
    


/* buffered reader...multiply */


import java.io.*;
class InputTest{
public class DataTypes {
      public static void main (String[] agrs)throws IOException
         {
            BufferedReader input=new BufferedReader(new InputStreamReader(System.in));
            String name1, name2;
            String strnum1, strnum2;
            int num1, num2, loanLimit = 0;
            System.out.println("Please enter your firstname: ");
            name1=input.readLine();
            System.out.println("Please enter your secondname: ");
            name2=input.readLine();
            System.out.println("Goodmorning " + name1 + " " + name2 + ", thanks for showing intrest in Milton Digital Networks. Enter your age: ");
            strnum1 = input.readLine();
            num1=Integer.parseInt(strnum1);
            System.out.println("Enter net worth sir: ");
            strnum2 = input.readLine();
            num2=Integer.parseInt(strnum2);
            loanLimit = num1*num2/100;
            System.out.println(name1 + " " +name2 + ", your loan limit is currently sh." +loanLimit +".");
            System.out.println("Please contact customer care for guidance.");
        }     
    }
    } 



    /*Loan calculator */

    import java.io.*;
    class NamingProg{
        public static void main(String[] args)throws IOException 
        {
            BufferedReader input = new BufferedReader(new InputStreamReader(System.in));
            String strnum1, strnum2, name1, name2, strpin;
            int num1, num2,loanLimit, personnalPin;        
            System.out.println("Enter your firstname: ");
            name1 = input.readLine();
            System.out.println("Enter your second name: ");
            name2 = input.readLine();
            System.out.println("Goodmorning "+ name1+" "+ name2+", please enter your age: "); 
            strnum1 = input.readLine();
            num1 = Integer.parseInt(strnum1);
            System.out.println("Thank you "+name1 + ", please enter your networth.");
            strnum2 = input.readLine();
            num2 = Integer.parseInt(strnum2);
            loanLimit = num1*num2/100;
            System.out.println("Please enter your mobile banking pin to continue, you will receive a text message containing your actual ballance.");        
            strpin = input.readLine();
            personnalPin = Integer.parseInt(strpin);
            System.out.println("Dear "+name1+" "+name2+", your Fuliza limit is currently sh. "+ loanLimit +", MDNets support team.");
            System.out.println("Please continue using our services to raise your Fuliza limit.");
            System.out.println("Milton Digital Networks, #KEEPMOVING!");
            
        }
    }



/* Scanner */


    
import java.util.Scanner;

public class Main{
    public static void main(String[] args){
        Scanner scanner = new Scanner(System.in);
        System.out.println("Enter your name: ");
        String name=scanner.nextLine();
        System.out.println("Enter your age: ");
        int age = scanner.nextInt();
        scanner.nextLine();
        System.out.println("where do you come from? ");
        String home=scanner.nextLine();
        System.out.println("You are: "+name);
        System.out.println("You are aged: "+age);
        System.out.println("From : "+home);
        
        }
    } 




 /*Graphical User Interface */



import javax.swing.JOptionPane;

public class Main{
    public static void main(String[] args){
        String name = JOptionPane.showInputDialog("Enter your name: ");
        int age = Integer.parseInt(JOptionPane.showInputDialog("Enter your age sir: "));
        JOptionPane.showMessageDialog(null, "Hello "+name+", your registration was successfull, you are aged "+age , "Millton Digital Nets", 0, null);
    }
}



/*Hypoteneus calculatir */


import java.util.Scanner;

public class Main{
    public static void main(String[] args){
        Scanner scanner = new Scanner(System.in); 
        double x;
        double y;
        double z;
        System.out.println("This system will calculate the hypotenues of your triangle.");
        System.out.println("Enter the heigth: ");
        x = scanner.nextDouble();
        System.out.println("Enter the base: ");
        y = scanner.nextDouble();
        z = Math.sqrt((x*x)+(y*y));
        System.out.println("The hypotenues of your triangle is: " +z);
    }
} 






/*Graphical User Interface project*/

import javax.swing.JOptionPane;
public class Main{
    public static void main(String args[]){
        String fnum1, fnum2, name;
        double num1, num2;
        name = JOptionPane.showInputDialog("Hello, enter your name please. ");
        fnum1 = JOptionPane.showInputDialog("Enter heigth: ");
        fnum2 = JOptionPane.showInputDialog("Enter your age: ");
        num1 = Double.parseDouble(fnum1);
        num2 = Double.parseDouble(fnum2);
        JOptionPane.showInternalMessageDialog(null, "Hi "+name+"! \nYou are "+num1+" metres tall at the age of "+num2, "Milton Digital Networks",JOptionPane.PLAIN_MESSAGE);
        System.exit(0);
    }
}



/* Electrict Token calculator*/

import java.util.Scanner;
class UnitCalc{
    public static void main(String ags[]){
        double x,w,q,y;
        Scanner in = new Scanner(System.in);
        System.out.println("Enter your name: ");
        String name = in.next();
        System.out.println("Enter the number of units you consumed: ");
        double units = in.nextDouble();
        if(units<20){
            x=units*12;
            System.out.println("Hi "+name+", Your outstanding electric bill is sh."+x+100);
        }
        else if(units<=30){
            w=units*15;
            System.out.println("Hi "+name+", Your outstanding electric bill is sh."+w+100);
        }
        else if(units<=40){
            y = units*17;
            System.out.println("Hi "+name+", Your outstanding electric bill is sh."+y+100);
        }
        else if(units>40){
            q = units*20;
            System.out.println("Hi "+name+", Your outstanding electric bill is sh."+q+100);

        }
    }
}



/*Electric GUI Bill calculator */


import javax.swing.JOptionPane;
import java.util.Scanner;
class UnitCalc{
    public static void main(String ags[]){
        double standingCharge=100;
        double bill;
        Scanner in = new Scanner(System.in);
        System.out.println("Enter your name: ");
        String name = in.nextLine();
        System.out.println("Enter the number of units you consumed: ");
        double units = in.nextDouble();
        if(units<20){
            bill=units*12+standingCharge;
        }
        else if(units<=30){
            bill=units*15+standingCharge;
        }
        else if(units<=40){
            bill = units*17+standingCharge;
        }
        else if(units>40){
            bill = units*20+standingCharge;
        }
        else{
            bill=0;
        }
        JOptionPane.showMessageDialog(null,"Hi "+name+".\nYour outstanding bill is "+bill+"sh.\nYou consumed "+units+" units this month.","KPLC, Kenya.", JOptionPane.PLAIN_MESSAGE);
    }
}




/*Class object*/

class Person {
    String name = "Milton";
    int age = 20;

    public static void main(String[] ags) {
        Person milton = new Person();
        milton.age = 40;
        System.out.println("Hi, your name is " + milton.name + " aged " + milton.age);
    }
}


/* CLASS EXTENDS METHOD */


public class Milton {
    int z;

    public void addition(int x, int y) {
        z = x + y;
        System.out.println("Hi, your sum is " + z);
    }

    public void subtraction(int x, int y) {
        z = x + y;
        System.out.println("Hi, your subtraction is " + z);
    }
}

class MyCariculum extends Milton {
    public void multiplication(int x, int y) {
        z = x * y;
        System.out.println("Your multiplication is " + z);
    }

    public static void main(String arg[]) {
        int a = 20;
        int b = 30;
        MyCariculum kip = new MyCariculum();
        kip.addition(a, b);
        kip.subtraction(a, b);
        kip.multiplication(a, b);
    }
}






/* OVERLOADED CLASS */


public class Milton {
    public int area(int L, int W) {
        return L * W;
    }

    public int area(int L, int W, int H) {
        return L * W * H;
    }

    public static void main(String ags[]) {
        Milton milt = new Milton();
        System.out.println("Antonios net worth is Ksh." + milt.area(4, 5) * 1000 + " Hahahaaaa");
        System.out.println("Miltons networth is Ksh." + milt.area(9, 2, 1) * 1000 + " Hahahaaa");

    }
}


/* Arrays */


import java.util.Arrays;

class cat1 {
    public static void main(String args[]) {
        int sum = 0;
        int[] my_array = { 1789, 2035, 1899, 1456, 2013, 1458, 2458, 1254, 1472, 2365, 1456, 2165, 1457, 2456 };
        Arrays.sort(my_array);
        for (int i = 0; i < my_array.length; i++) {
            sum += my_array[i];
        }

        System.out.println(sum);
    }

}



/* Arrays continuation */


class cat1 {
    public static void main(String args[]) {
        String S1 = "Java Programming";
        String S2 = "is tought";
        String S3 = "at Calorado State";
        int iSize = S3.length() + 3;
        System.out.println(iSize);
        char cChar = S1.charAt(10);
        System.out.println(cChar);
        int iIndex = S2.indexOf("p");
        System.out.println(iIndex);
        String sSubstr = S1.substring(1, 7);
        System.out.println(sSubstr);
        boolean bEquals = S2.equals("is tought");
        System.out.println(bEquals);

    }

}


/*This program prompts the user to enter a grade*/


import java.util.Scanner;

class cat1 {
    public static void main(String args[]) {
        int grade;
        String school;
        Scanner scan = new Scanner(System.in);
        System.out.println("Enter your grade: ");
        grade = scan.nextInt();
        if (grade >= 0) {
            if (grade <= 5) {
                school = "Elementary School";
            } else if (grade <= 8) {
                school = "Junior School";
            } else if (grade <= 12) {
                school = "High School";
            } else {
                school = "College";
            }
            System.out.println(school);
        } else {
            System.out.println("Please enter a grade greater or equals to zero! ");
        }
    }

}


/* Grading system */


import java.util.Scanner;

class cat1 {
    public static void main(String args[]) {
        int grade;
        String school;
        Scanner scan = new Scanner(System.in);
        System.out.println("Enter your grade: ");
        grade = scan.nextInt();
        /* Takes a grade only greater than zero */
        if (grade >= 0) {
            if (grade <= 5) {
                school = "Elementary School";
            } else if (grade <= 8) {
                school = "Junior School";
            } else if (grade <= 12) {
                school = "High School";
            } else {
                school = "College";
            }
            System.out.println("Your grade is: " + grade);
            System.out.println("Your set school is: " + school);
        } else {
            System.out.println("Please enter a grade greater or equals to zero! ");
        }
    }

}

