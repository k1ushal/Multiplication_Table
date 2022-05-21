# Multiplication_Table
This is just a simple C programme to produce multiplication Table of any number entered by user. Created by @k1ushal Just a beginner practice.


<pre>
#include <stdio.h>

int main()
{
	printf("***Multiplication Table finder of any numbers***\n\n\n\n");
	int a, i;
	printf("Enter any number: ");
	scanf("%d", &i);
	printf("\n\n");
	for (a = 1; a <= 10; a++)
	{
		printf("%d x %d = %d \n\n", i, a, i * a);
	}
	printf("\n\n");
	printf("Thanks for using this program - Kushal\n\n");

	return 0;
} </pre>
