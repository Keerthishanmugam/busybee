# busybee
import java.io.*;
import java.util.*;
public class solution {
public static void main(String []args){
int[] array=new int[6];
for(int i=0;i<array.length;i++)
array[i]=i;
int sum=0;
for(int result : array)sum +=result;
System.out.println(sum);
}
}
