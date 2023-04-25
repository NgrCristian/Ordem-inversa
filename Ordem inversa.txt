#include<stdio.h>
int main()

{
 int valor[10], i;

 for(i=0; i<10; i++)
 {
 printf("dIGITE O NMR: \n ", i+1);
 scanf("%d", &valor[i]);
 }
 printf("\n A ORDEM INVERSA EH: :\n");

 for(i=0; i<10; i++)
 printf("%d\n", valor[9-i]); 
}
