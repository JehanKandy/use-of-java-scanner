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


