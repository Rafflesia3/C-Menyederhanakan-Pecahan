# C-Menyederhanakan-Pecahan

    #include <stdio.h>

    int pecahan();
    int main(){
        pecahan();
    }

    int pecahan(){

    int a,b,l,t;

    printf("\t\t Pelita Bangsa \n\n");
    printf("=========================================\n");
    printf("Nama    : Rafi Alwan Setyawan \nNIM     : 311810325 \nKelas   : TI.18.D7 \n");
    printf("=========================================\n");
    printf("\t     Fungsi Menyederhanakan Pecahan\n");

    printf("\nMasukan pembilang :");
    scanf("%d",&a);
    printf("Masukan penyebut :");
    scanf("%d",&b);
    t=a/b;
    l=a%b;
    if(a%b == 0)
        printf("\nBilangan (%d/%d) \ndi sederhanakan menjadi %d",a,b,t);
    else if (a%b != 0)
        printf("\nBilangan (%d/%d) \ndi sederhanakan menjadi (%d %d/%d)\n\n",a,b,t,l,b);

    }
    
Hasil
![img](https://github.com/Rafflesia3/C-Menyederhanakan-Pecahan/blob/master/C++%20Menyederhanakan%20Pecahan.png?raw=true)
