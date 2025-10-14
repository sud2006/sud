//klavyeden girilen üç sayıdan en büyüğünü ekrana yazdıran c kodunu yazınız.

#include <stdio.h>

int main()
{
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
    printf("%d",max);
    return 0;
}
