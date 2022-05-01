# use-of-java-scanner
java.util.scanner
<br><br>
<b>How to use java Scanner </b>

<b>Code Explain</b> 
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
