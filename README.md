# Cospro6
int main(void)
{
	int num=0;
	
	while(num<5)
	{
		printf("Hello World! %d\n", num);
		num++;
	}
	return 0;	
/////////////////
#include<stdio.h>

int main(void)
{

	int dan = 1;
	int num = 0;

	for (dan = 1; dan <= 9; dan++)
	{
		for (num = 0; num < 10; num++)
		{
			printf(" %d x %d = %d \\n", dan, num, dan * num);
		}
		printf("\\n\\n");
	}


	return 0;
}

/*
	double total = 0.0;
	double input = 0.0;

	int num = 0;

	for (; input >= 0.0;)
	{
		total += input;
		printf(" 실수를 입력(minus to quit) :");
		scanf_s("%lf", &input);
		printf(" + %lf", input);
		num++;
	}

	printf("\\n");
	printf(" total sum = %lf \\n\\n", total);

	printf("평균 : %lf \\n\\n", total / (num - 1));
*/

/*
int total = 0;
int i = 0, sum = 0;

printf("0부터 num 까지 덧셈 sumd은?");
scanf_s("%d", &sum);
printf("%d", total);

for (i = 1; i <= sum; i++)
{
	total += i;
	printf(" + %d", i);
}

printf(" = %d \\n", total);
*/

/*
	int num = 0;

	for (num = 0; num < 3;num++)
	{
		printf("Hi for \\n");
	}

	num = 0;
	while (num < 3)
	{
		printf("Hi while \\n");
		num++;
	}
*/

/*
	int num = 0;

	do
	{
		printf("%d \\n", num);
		num++;
	} while (num < 0);
*/

/*
	int dan = 1, num = 0;

	while (dan <= 9)
	{
		num = 0;
		while (num <= 9)
		{
			printf(" %d x %d = %d \\n", dan, num, dan * num);
			num++;
		}
		dan++;
		printf("\\n\\n\\n");
	}
*/

/*
	int dan = 0, num = 0;

	printf("몇 단? : ");
	scanf_s("%d", &dan);

	while (num <= 9)
	{
		printf(" %d x %d = %d \\n", dan , num, dan * num);
		num++;
	}
	return 0;
*/

/*
	int num = 0;

	while (num < 3)
	{
		printf("%d \\n", num);
		num++;
	}

	return 0;
*/
