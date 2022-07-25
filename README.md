import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner s=new Scanner(System.in);
        int target,range,count=0;
        range=s.nextInt();
        target=s.nextInt();
        for(int i=1;i<=range;i++){
            for(int j=i+1;j<=range;j++){
                if((i+j)==target){
                    count++;
                }
            }
        }
        System.out.println(count);
    }
}
