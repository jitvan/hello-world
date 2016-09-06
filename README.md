# hello-world
my first repository!!!!
lets code!!!!
import java.util.Scanner;

import java.math.BigInteger;

 
class BigFactorial

{

  public void main()

  {

    int n, c;

    BigInteger inc = new BigInteger("1");

    BigInteger fact = new BigInteger("1");

 
    Scanner input = new Scanner(System.in);
System.out.println("enter");
 int l=input.nextInt();

    for(int i=1;i<=l;i++)

    {

        n = input.nextInt();

 
    for (c = 1; c <= n; c++) {

      fact = fact.multiply(inc);

      inc = inc.add(BigInteger.ONE);

    }

 
    System.out.println(""+fact);

  }

  }

} 
