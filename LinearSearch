import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.println("How many numbers?");
        int n = sc.nextInt();

        int[] arr = new int[n];

        System.out.println("Enter the numbers:");
        for (int i = 0; i < n; i++) {
            arr[i] = sc.nextInt();
        }

        System.out.println("Number to search:");
        int key = sc.nextInt();

        int foundIndex = -1;

        for (int i = 0; i < n; i++) {
            if (arr[i] == key) {
                foundIndex = i;
                break;
            }
        }

        if (foundIndex == -1) {
            System.out.println("Number not found.");
        } else {
            System.out.println("Number found at index " + foundIndex);
        }
    }
}
