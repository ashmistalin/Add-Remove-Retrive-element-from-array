# Add-Remove-Retrive-element-from-array

## AIM:
To write a java program to add, retrieve and remove the element from the ArrayList.

## PROCEDURE:

## PROGRAM:
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
## OUTPUT:
```
C:\Users\Dell\.jdks\openjdk-19.0.2\bin\java.exe "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.3.3\lib\idea_rt.jar=10497:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2022.3.3\bin" -Dfile.encoding=UTF-8 -Dsun.stdout.encoding=UTF-8 -Dsun.stderr.encoding=UTF-8 -classpath "C:\Users\Dell\IdeaProjects\java full stack\out\production\java full stack" Arraylist1
ArrayList: [10, 20, 30]
First element: 10
ArrayList after removing element at index 1: [10, 30]

Process finished with exit code 0
```

## RESULT:
Thus the java program to add,remove and retrive the elements of ArrayList is created and the output is verified.
