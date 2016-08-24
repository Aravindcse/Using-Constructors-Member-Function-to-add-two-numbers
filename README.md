import java.lang.*;
import java.io.*; 
class calc
{
 int n1,n2;
 
 calc(int a, int b)
 {
  n1 = a;
  n2 = b;
 }
 public void assign(int a, int b)
 {
   n1 = a;  
   n2 = b;  
 } 
 public void sum()
 {
  System.out.println("Sum of"+n1+"and"+n2+"is"+(n1+n2));
 }
}
 
class add
{
 public static void main(String args[])
 {
  calc c;   
  c = new calc(20,10);  
  calc c = new calc(30, 10);
  c.assign(30,10)
  c.sum();
 }
}
