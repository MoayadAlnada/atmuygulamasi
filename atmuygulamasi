#include <stdio.h>
#include <stdlib.h>


int main() {
  int secenek;
  float Bakiye = 0;
  float Cekme;
  float Yatirma;
do{
  printf("\nATM'ye Hos geldiniz\n");
  printf("1. Bakiye sorgulama\n");
  printf("2. Para cekme\n");
  printf("3. Para yatirma\n");
  printf("4. Cikis\n");
  printf("Seciminizi yapin: ");
  scanf("%d", &secenek);

  switch(secenek) {
    case 1:
      printf("Guncel Bakiyeniz: $%.2f\n", Bakiye);
      break;
    case 2:
      printf("Cekmek istediginiz tutari girin: ");
      scanf("%f", &Cekme);
      if(Cekme > Bakiye) {
        printf("Yetersiz Bakiye!\n");
      }
      else {
        Bakiye = Bakiye - Cekme;
        printf("$%.2f Cekildi\n", Cekme);
        printf("Guncel Bakiyeniz: $%.2f\n", Bakiye);
      }
      break;
    case 3:
      printf("Yatirmak istediginiz tutari girin: ");
      scanf("%f", &Yatirma);
      Bakiye = Bakiye + Yatirma;
      printf("$%.2f Yatirildi\n", Yatirma);
      printf("Guncel Bakiyeniz: $%.2f\n", Bakiye);
      break;
    case 4:
      printf("ATM'yi kullandiginiz icin tesekkur ederiz\n");
      break;
    default:
      printf("Hatali tuslama yaptiniz\n");
      break;
  }
}while(secenek != 4);

  return 0;
}
