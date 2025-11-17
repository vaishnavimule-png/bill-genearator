# bill-genearator
stationery shop
#include <stdio.h>

int main() {
    char item[10];
    int quantity;
    float price,total=0;
    printf("\n------stationary bill generator-----\n");
     printf("enter item name:");
     scanf("%s",&item);
     printf("enter quantity:");
     scanf("%d", &quantity);
     printf("enter price per item:");
     scanf("%f",&price);
     total=quantity*price ;
     printf("total:%f\n",total);
     printf("\n-----thank you-----\n");
     return 0;
}
