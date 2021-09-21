# greatest-of-three-numbers
import java.util.Scanner;
public class BiggestNumber
{
public static void main(String[] args)
{
int x, y, z;
Scanner s = new Scanner(System.in);
System.out.print(&quot;Enter the first number:&quot;);
x = s.nextInt();
System.out.print(&quot;Enter the second number:&quot;);
y = s.nextInt();
System.out.print(&quot;Enter the third number:&quot;);
z = s.nextInt();
if(x &gt; y &amp;&amp; x &gt; z)
{
System.out.println(&quot;Largest number is:&quot;+x);
}
else if(y &gt; x &amp;&amp; y&gt;z)
{
System.out.println(&quot;Largest number is:&quot;+y);
}
else
{
System.out.println(&quot;Largest number is:&quot;+z);
}
}
}
