import java.io.*;
import java.util.*;
import java.util.Arrays;
public class Array
{
public static void main(String args[])
{
Scanner s=new Scanner(System.in);
int n=s.nextInt();
int a[]=new int[n];
System.out.println
for(i=0;i<n;i++)
{
a[i]=s.nextInt();
}
Arrays.sort(a);
for(i=0;i<n;i++)
{
System.out.println(a[i]);
}
}
}
