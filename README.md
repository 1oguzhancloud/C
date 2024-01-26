#include <stdio.h>
#include <stdlib.h>
int main()
{
  int sinav1,sinav2,sinav3,proje,ortalama,toplam;
  
        printf("1 sinav notunu giriniz: ");
        scanf("%d", &sinav1);
        printf("2 sinav notunu giriniz: ");
        scanf("%d", &sinav2);
        printf("3 sinav notunu giriniz: ");
        scanf("%d", &sinav3);
        printf("proje notunu giriniz: ");
        scanf("%d", &proje);    
        
        toplam= sinav1+sinav2+sinav3+proje;
        ortalama=toplam/4;
        
    if (ortalama>=50 && ortalama<=60)
    {
        printf("dd ile gectiniz");
    }
    else if (ortalama>60 && ortalama<=70)
    {
        printf("cc ile gectiniz");
    }
    else if (ortalama>70 && ortalama<=84)
    {
        printf("bb ile gectiniz");
    }
    else if (ortalama>=85)
    {
        printf("aa ile gectiniz");
    }
    else
    {
        printf("kaldiniz");
    }   

return 0;
}

