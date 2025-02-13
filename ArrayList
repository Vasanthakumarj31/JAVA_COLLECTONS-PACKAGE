import java.util.Collection;
import java.util.List;
import java.util.ArrayList;
import java.util.Comparator;
import java.util.Collections; // Correct import for sorting


public class Main {
    public static void main(String[] args) {
        
        Comparator<Integer> com = new Comparator<Integer>() {
            public int compare(Integer a, Integer b) {
                // Compare based on the last digit of the numbers (a % 10, b % 10)
                return Integer.compare(a % 10, b % 10);
            }
        };

        List<Integer> obj = new ArrayList<Integer>();
        obj.add(56);
        obj.add(71);
        obj.add(69);
        obj.add(93);

        Collections.sort(obj, com); // Corrected to use Collections.sort
        System.out.println(obj);
    }
}
