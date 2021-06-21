import java.util.*;
public class File1 {
public static void main(String[] args) {
int n, e_sum=0, o_sum=0;
Scannet obj = new Scanner(system.in);
System.out.println("Enter Array size");
n = obj.nextInt();
int a[] = new int[n];
for(int i=0; i<n; i++)
{
a[i] = obj.nextInt();
}
for(int i=0; i<n; i++)
{
If(a[i]%2==0 && i%2==0)
e_sum = e_sum+a[i];
else if(a[i]%2==1 && i%2==1)
O_sum = o_sum+a[i];
}




