# weekend-or-working-day-in-java-by-using-Switch-statement
import java.util.Scanner;

public class weekendorworking {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		System.out.println("Enter the day :");
		String day = input.nextLine();
		switch(day) {
		case ("Monday"):
			System.out.println("uff, working day");
			break;
		case ("Tuesday"):
			System.out.println("uff, working day");
			break;
		case ("Wednesday"):
			System.out.println("uff, working day");
			break;
		case ("Thusday"):
			System.out.println("uff, working day");
			break;
		case ("Friday"):
			System.out.println("uff, working day");
			break;
		case ("saturday"):
			System.out.println("Heyy its weekend");
			break;
		case ("Sunday"):
			System.out.println("Heyy its weekend");
		default:
			System.out.println("Please Check once and Enter Correct Name");
		}input.close();
	}

}
