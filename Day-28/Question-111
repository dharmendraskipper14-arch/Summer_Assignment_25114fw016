import java.util.Scanner;
import java.util.Random;

class TicketBooking {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Random rand=new Random();
    

        int seats = rand.nextInt(100);

        System.out.print("Enter number of tickets: ");
        int tickets = sc.nextInt();

        if (tickets <= seats) {
            seats -= tickets;
            System.out.println("Booking Successful");
            System.out.println("Remaining Seats: " + seats);
        } else {
            System.out.println("Seats Not Available");
        }

        sc.close();
    }
}
