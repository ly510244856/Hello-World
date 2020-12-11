# Hello-World
This is my first code at github

#-------------------exchange two number----------------------
#include <stdio.h>

int main() 
{ 
	int a, b, temp;
	printf("please input your number what you want to exchange:");
	scanf_s("%d %d", &a, &b); 
	temp = a; a = b; b = temp; 
	printf("a = %d,b = %d", a, b);
	return 0; 
}

