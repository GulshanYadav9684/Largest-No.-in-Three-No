# Largest-No.-in-Three-No
Here in this example you will understand how to print the largest number in 3 no using &amp;&amp; operator.


#include <stdio.h>

void main()
{
	int x=10;
	int y=20;
	int z=30;
	
	x>y && x>z && printf("X is greater=%d",x);
		y>x && y>z && printf("y is greater=%d",y);
			z>x && z>y && printf("z is greater=%d",z);

}
