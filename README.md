# 3num
Program in C that checks the equality that exists between 3 numbers. 
#include <stdio.h>
#include <stdlib.h>

int main(int argc, char *argv[])
{
  int a,b,c;

   printf("Test con tres numeros: ");
   printf("\n");
   scanf("%d %d %d", &a, &b, &c);

   if((a + b) == c)
   printf("\nIguales, %d + %d = %d", a, b, c);
   else if ((a + c) == b)
   printf("\nIguales, %d + %d = %d", a, c, b);
   else if ((b + c) == a)
   printf("\nIguales, %d + %d = %d", b, c, a);
   printf("\n\n");
   
  system("PAUSE");	
  return 0;
}
