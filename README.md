// Verilen 3 sayının ortalamasını bulunuz.
# uc-sayi-ort-hsp

#include <stdio.h>
int main(){
float sayi1,sayi2,sayi3;

printf("ilk sayiyi giriniz:");
scanf("%f",&sayi1);
printf("ikinci sayiyi giriniz:");
scanf("%f",&sayi2);
printf("ucuncu sayiyi giriniz:");
scanf("%f",&sayi3);

float ortalama = (sayi1 + sayi2 + sayi3) / 3;

printf("girilen sayilarin ortalamasi: %f",ortalama);

return 0;
}
