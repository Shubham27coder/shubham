# shubham
just another repository
import java.io.*;
class rectangle
{
public static void main (String args[]) throw IOException
{
BufferReadred in = new BufferReadred (new InputStreamReader(System.in));
int l,b,area;
l= Integer.parseInt(in.readLine());
b= Integer.parseInt(in.readLine());
area= l*b;
System.out.println("area of rectangle"+area);
}
}
