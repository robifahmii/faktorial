import java.io.*;
public class Faktorial {
    public static void main(String[] args) {
        String input = "";
        int i, jlh = 1;
        BufferedReader buffer = new BufferedReader(new InputStreamReader(System.in));
        System.out.print("Input bilangan n!, n : ");
        try {
            input = buffer.readLine();
        } catch (Exception e) {
        }
        int a = Integer.valueOf(input);
        System.out.print("Penyelesaian faktorial\n" + a + "! = ");
        if (a < 1) {
            System.out.println("Silahkan masukkan angka lebih besar dari 0");
        } else {
            for (i = 1; i <= a; i++) {
                System.out.print(i);
                if (i < a) {
                    System.out.print(" x ");
                }
                jlh = jlh * i;
            }
            System.out.println("\n   = " + jlh);
        }
    }
}
