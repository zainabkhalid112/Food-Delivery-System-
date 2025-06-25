// TestOrder.java
public class TestOrder {
    public static void main(String[] args) {
        FoodItem item = new FoodItem("Burger", 350);
        System.out.println("Ordered: " + item.getName() + " | Price: " + item.getPrice());
    }
}
