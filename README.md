# print-the-values
import java.util.Scanner;


public class ReadAndPrint {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter something: ");
        String input = scanner.nextLine();

        System.out.println("You entered: " + input);


        scanner.close();
    }
}


OUTPUT:
Enter something: Hello, World!
You entered: Hello, World!
