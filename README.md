# MARKS
AKSHITA
#include<stdio.h>

int main(){
	int x;
	printf("Enter marks:");
	scanf("%d",&x);
	if(x>=85&&x<=100)
		printf("Grade A");
	else if(x>=70&&x<=84)
		printf("Grade B");
	else if(x>=55&&x<=69)
		printf("Grade C");
	else if(x>=40&&x<=54)
		printf("Grade D");
	else
		printf("Grade F");
}
