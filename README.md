#include <stdio.h>
int main()
{
int num;

printf("Enter a four-digit random number: ");
scanf("%d", &num);

/* For getting the 4 numbers*/
printf("%d\n", num / 1000); 
printf("%d\n", (num / 100) % 10);
printf("%d\n", (num / 10) % 10);
printf("%d\n", num % 10);

return 0;
}
