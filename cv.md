1. **Name:**  
Alexey Medvedev
2. **Contacts:**  
    **2.1** Tambov  
    **2.2** tel: 8900000000  
    **2.3** discord: spiritlm#6028  
    **2.4** telegram: spiritlm
	
3. **About me**  
At the moment I work as a network-system administrator in a large gas industry company. In the near future I plan to change my specialty in the direction of backend or frontend development. I learn quickly and assimilate new information.
4. **Skills**  
   Basic Object-oriented programming skills (Java, Python). 
5. **Сode example**  
```
import java.text.DecimalFormat;
import java.util.Scanner;

public class Solving {
    public static void main(String[] args) {
        Diskriminant Diskr = new Diskriminant();

        Scanner in = new Scanner(System.in);
        System.out.print("Введите а: ");
        double a = in.nextDouble();

        System.out.print("Введите b: ");
        double b = in.nextDouble();

        System.out.print("Введите c: ");
        double c = in.nextDouble();

        in.close();

        double d = (Math.pow(b, 2)) - (4 * a * c);

        DecimalFormat decimalFormat = new DecimalFormat("#.###");
        String result = decimalFormat.format(d);
        System.out.println(("Дискриминант равен: " + result));

        if (d > 0) {
            double x1 = (-b + Math.sqrt(d) / (2 * a));
            String resultX1 = decimalFormat.format(x1);
            System.out.println(("x1 = : " + resultX1));

            double x2 = (-b - Math.sqrt(d) / (2 * a));
            String resultX2 = decimalFormat.format(x2);
            System.out.println(("x2 = : " + resultX2));

        } else if (d == 0) {
            double x1 = (-b + Math.sqrt(d) / (2 * a));
            System.out.println("x1 = " + x1);
        }
        else {
            System.out.println("Корней нет");
        }
    }
}
```
6. **Education**  
Higher education in the specialty "Organization and information security technologies"
7. **English language level**  
A1 - I read and translate with a dictionary