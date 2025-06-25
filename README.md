// MainUI.java
import javax.swing.*;

public class MainUI {
    public static void main(String[] args) {
        JFrame frame = new JFrame("Food Delivery System");
        frame.setSize(400, 300);
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);

        JLabel label = new JLabel("Welcome to the Food Delivery App");
        frame.add(label);

        frame.setVisible(true);
    }
}
