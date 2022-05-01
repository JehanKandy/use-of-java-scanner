# use-of-java-scanner
java.util.scanner
<br><br>
<b>How to use java Scanner </b>

<b>Code Explain</b> 
<br>

        import java.util.Scanner;

        public class scanner_java {

            public static void main(String[] args) {
                Scanner stdname = new Scanner(System.in);

                System.out.println("Enter First Name : ");
                String fname = stdname.nextLine();

                System.out.println("Enter Last Name : ");
                String lname = stdname.nextLine();

                System.out.println("You Name is : "+fname+" "+lname);
            }
        }
      
<br>     
in oder  to above code 

        import java.util.Scanner;
        
There is a package named util. it has Scanner class
<br><br>

so when we want to get inputs from user we have to use this Scanner class<br>

the basic of java code you can visite following link: <br>
https://github.com/JehanKandy/First-Coding-with-JAVA

<br><br>

then we have ti create a Scanner object

        Scanner stdname = new Scanner(System.in);

Then I get the first name as 
<br> String named fname 

<br>and also it same for the last name
<br>
first Name: <br>
        String fname = stdname.nextLine();
last Name: <br>
        String lname = stdname.nextLine();
<br><br>

