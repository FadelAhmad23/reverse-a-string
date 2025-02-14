# reverse-a-string
import java.util.Scanner;

public class ReverseString {
    public static String reverse(String input) {
        StringBuilder reversed = new StringBuilder(input);
        return reversed.reverse().toString();
    }

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        System.out.print("Basketball: ");
        String input = scanner.nextLine();
        System.out.println("Reversed: " + reverse(input));
        scanner.close();
    }
}
