import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
  Scanner sc = new Scanner(System.in);
   
    int ball = sc.nextInt(); 
    int run = sc.nextInt(); 
    int runsc = sc.nextInt(); 
    int ballbo = sc.nextInt(); 
    float over = ball / 6; 
    int overf = ballbo / 6; 
    int f1 = ballbo % 6;
    float f2 = overf + (float)f1 * 1 / 10;
    float curra = runsc / f2; 
    float totra = run / over; 
    System.out.println((int)over);
    System.out.println(f2);
    System.out.printf("%.1f\n" ,curra);
    System.out.printf("%.1f\n" ,totra);
    if(curra >= totra)
        System.out.println("Eligible to Win");
    else
        System.out.println("Not Eligible to Win");

    }
}
