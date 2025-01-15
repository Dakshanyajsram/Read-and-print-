import java.util.Scanner;

public class ReadAndPrint {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Prompt the user to enter some text
        System.out.print("Enter something: ");
        String input = scanner.nextLine();

        // Print the entered text
        System.out.println("You entered: " + input);

        scanner.close();
    }
}


 
OUTPUT: 
Enter something: java program is complex
You entered: java program is complex
