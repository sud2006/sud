//üç sayıdan büyük olanı c kodu ile ekrana yazdırınız.

#include <stdio.h>
int main(){

   int a,b,c,max;

     max=a;
     printf("üç sayı giriniz.\n");
     scanf("%d%d%d",&a,&b,&c);
   
   if(b>max)
  {
    max=b;
  }
  
   if(c>max)
  {
    max=c;
  }
    printf("max=%d",max);
     
     return 0;
}
