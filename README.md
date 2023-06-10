# Add-Remove-Retrive-element-from-array

```
import java.util.ArrayList;

public class Arraylist1 {
    public static void main(String[] args) {
        ArrayList<Integer> numbers = new ArrayList<>();
        numbers.add(10);
        numbers.add(20);
        numbers.add(30);

        System.out.println("ArrayList: " + numbers);

        int firstElement = numbers.get(0);
        System.out.println("First element: " + firstElement);

        numbers.remove(1);
        System.out.println("ArrayList after removing element at index 1: " + numbers);
    }
}
```
