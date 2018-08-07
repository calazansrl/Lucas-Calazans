# Lucas-Calazans
Comando de atribuição de variáveis

#include <stdio.h>
#include <stdlib.h>

int main()
{
   float a,b,c,delta,i,z;
   #1
   a = 3;
   printf("%.2f\n",a);

   i = a+3;
   printf("%.2f\n",i);

   #3
   i=i+1;
   printf("%.2f\n",i);

   #4
   b=a+i;
   printf("%.2f\n",b);

   #5
   b=i+a;
   printf("%.2f\n",b);

   #6
   a=((2*b)+i);
   printf("%.2f\n",a);


   #7
   a=2*(b+i);
   printf("%.2f\n",a);

   #8
   delta = ((b*b)-4*a*i);
   printf("%.2f\n",delta);

   #9
   b=a/i;
   printf("%.2f\n",b);

   #10
   b=2+(a/i);
   printf("%.2f\n",b);

   #11
   b=2+(a/i);
   printf("%.2f\n",b);

   #12
   c=a+(b/2);
   printf("%.2f\n",c);

   #13
   c=(a+b)/2;
   printf("%.2f\n",c);
   #14
   z=a[b/2+((c+i)/2)]
   printf("%.2f\n",z);*/
   return 0;
}
