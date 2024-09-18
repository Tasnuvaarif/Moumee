//1.
class Customer {
    int customerID;
    String customerName;
    String cPhoneNumber;
    double totalPrice;
    public Customer(int id, String name, String phone, double price) {
        customerID = id;
        customerName = name;
        cPhoneNumber = phone;
        totalPrice = price;
    }
    
    public double getPayableAmount() {
        return totalPrice * 0.95;
        }
}

public class Main {
    public static void main(String[] args) {
        Customer c1 = new Customer(101, "John Doe", "123-456-7890", 1000.0);
        Customer c2 = new Customer(102, "Jane Smith", "098-765-4321", 1500.0);
        Customer c3 = new Customer(103, "Emily Clark", "555-666-7777", 1200.0);
}
}

//2.

public class Main {
    public static void main(String[] args) {
        Customer c1 = new Customer(101, "John Doe", "123-456-7890", 1000.0);
        Customer c2 = new Customer(102, "Jane Smith", "098-765-4321", 1500.0);
        Customer c3 = new Customer(103, "Emily Clark", "555-666-7777", 1200.0);
        System.out.println("Payable Amount of C1 (after 5% discount): " + c1.getPayableAmount());
        System.out.println("Payable Amount of C2 (after 5% discount): " + c2.getPayableAmount());
        System.out.println("Payable Amount of C3 (after 5% discount): " + c3.getPayableAmount());
}
}
