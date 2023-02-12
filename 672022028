#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
#include <windows.h>
#include <math.h>
#define PHI 3.14
#define PI 3.1415926535897932384626433832795028841971693993751058209749445923078164062862089986280348253421170679821480865132823066470938446095505822317253594081284811174502841027019385211055596446229489549303819644288109756659334461284756482337867831652712019091456485669234603486104543266482133936072602491412737245870066063155881748815209209628292540917153643678925903600113305305488204665213841469519415116094330572703657595919530921861173819326117931051185480744623799627495673518857527248912279381830119491298336733624406566430860213949463952247371907021798609437027705392171762931767523846748184676694051320005681271452635608277857713427577896091736371787214684409012249534301465495853710507922796892589235420199561121290219608640344181598136297747713099605187072


void gotoxy(int x, int y){
    COORD coord;
    coord.X = x;
    coord.Y = y;
    SetConsoleCursorPosition(GetStdHandle(STD_OUTPUT_HANDLE), coord);
}

void main()
{
    system("cls");
    system("COLOR F9");
    cover();
    int position = 1;
    int keyPressed = 0;
    int maxoption = 3;
    gotoxy(55,10);
    printf("MENU UTAMA");
    while(keyPressed != 13){
        gotoxy(45,14);
        arrowhere(1,position); printf(" 1. PingPoroLanSudo");
        gotoxy(45,15);
        arrowhere(2,position); printf(" 2. SinCosTan");
        gotoxy(45,16);
        arrowhere(3,position); printf(" 3. Hitung Keliling dan Luas");
        gotoxy(45,17);
        arrowhere(4,position); printf(" 4. Hitung Akar Kuadrat");
        gotoxy(45,18);
        arrowhere(5,position); printf(" 5. Exit");
        keyPressed = getch();
        if(keyPressed == 80 && position !=5){
            position++;
        }else if(keyPressed == 72 && position !=1){
            position--;
        }else{
            position = position;
        }
    }
    printf(" Select Option ,%d \n",position);
    int x = position;
    int a;
    int b;

    switch (x){
        case 1:
            kalkulator();
            main();
            break;
        case 2:
            Sincostan();
            main();
            break;
        case 3:
            hitkellu();
            main();
            break;
        case 4:
            hitakua();
            main();
            break;
        case 5:
            system("cls");
            printf("PRADENA TIARA MAHARANI - 672022028");
            exit(0);
    }
}

void kalkulator()
{
    system("cls");
    system("COLOR F9");
    cover();
    int position = 1;
    int keyPressed = 0;
    int maxoption = 3;
    gotoxy(52,10);
    printf("PingPoroLanSudo");
    while(keyPressed != 13){
        gotoxy(47,14);
        arrowhere(1,position); printf(" 1. PERKALIAN");
        gotoxy(47,15);
        arrowhere(2,position); printf(" 2. PEMBAGIAN");
        gotoxy(47,16);
        arrowhere(3,position); printf(" 3. PENJUMLAHAN");
        gotoxy(47,17);
        arrowhere(4,position); printf(" 4. PERKURANGAN");
        gotoxy(47,18);
        arrowhere(5,position); printf(" 5. Return Menu Utama");
        keyPressed = getch();
        if(keyPressed == 80 && position !=5){
            position++;
        }else if(keyPressed == 72 && position !=1){
            position--;
        }else{
            position = position;
        }
    }
    printf(" Select Option ,%d \n",position);
    int x = position;
    int a;
    int b;

    switch (x){
        case 1:
            kali();
            break;
        case 2:
            bagi();
            kalkulator();
            break;
        case 3:
            tambah();
            kalkulator();
            break;
        case 4:
            kurang();
            kalkulator();
            break;
        case 5:
            main();
            break;


    }
}

void kali()
{
    int pilih;
    rara:
    system("cls");
    co();
    float a,b,c;
    gotoxy(50,8);printf("KALKULATOR PERKALIAN");
    gotoxy(22,12);printf("Masukkan Angka Pertama: ");
    scanf("%f",&a);
    gotoxy(22,13);printf("Masukkan Angka Kedua: ");
    scanf("%f",&b);
    c=a*b;
    gotoxy(22,15);printf("Hasil dari %.2f * %.2f adalah %.2f",a,b,c);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Perkalian(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        kalkulator();
    }
    else{
        system("cls");
        goto temp;
    }

}

void bagi(){
    int pilih;
    rara:
    system("cls");
    co();
    float a,b,c;
    gotoxy(50,8);printf("KALKULATOR PEMBAGIAN");
    gotoxy(22,12);printf("Input nilai 1: ");
    scanf("%f",&a);
    gotoxy(22,13);printf("input nilai 2: ");
    scanf("%f",&b);
    c=a/b;
    gotoxy(22,15);printf("Hasil dari %.2f / %.2f adalah %.2f",a,b,c);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Pembagian(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        kalkulator();
    }
    else{
        system("cls");
        goto temp;
    }
}

void tambah(){
    int pilih;
    rara:
    system("cls");
    co();
    float a,b,c;
    gotoxy(50,8);printf("KALKULATOR PERTAMBAHAN");
    gotoxy(22,12);printf("Input nilai 1: ");
    scanf("%f",&a);
    gotoxy(22,13);printf("input nilai 2: ");
    scanf("%f",&b);
    c=a+b;
    gotoxy(22,15);printf("Hasil dari %.2f + %.2f adalah %.2f",a,b,c);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Pertambahan(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        kalkulator();
    }
    else{
        system("cls");
        goto temp;
    }
}

void kurang(){
    int pilih;
    rara:
    system("cls");
    co();
    float a,b,c;
    gotoxy(50,8);printf("KALKULATOR PENGURANGAN");
    gotoxy(22,12);printf("Input nilai 1: ");
    scanf("%f",&a);
    gotoxy(22,13);printf("input nilai 2: ");
    scanf("%f",&b);
    c=a-b;
    gotoxy(22,15);printf("Hasil dari %.2f - %.2f adalah %.2f",a,b,c);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Pengurangan(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        kalkulator();
    }
    else{
        system("cls");
        goto temp;
    }
}

void Sincostan()
{
    system("cls");
    system("COLOR F9");
    cover();
    int position = 1;
    int keyPressed = 0;
    int maxoption = 3;
    gotoxy(55,10);
    printf("SinCosTan");
    while(keyPressed != 13){
        gotoxy(47,14);
        arrowhere(1,position); printf(" 1. Sinus");
        gotoxy(47,15);
        arrowhere(2,position); printf(" 2. Cosinus");
        gotoxy(47,16);
        arrowhere(3,position); printf(" 3. Tangen");
        gotoxy(47,17);
        arrowhere(4,position); printf(" 4. Return Menu Utama");
        keyPressed = getch();
        if(keyPressed == 80 && position !=4){
            position++;
        }else if(keyPressed == 72 && position !=1){
            position--;
        }else{
            position = position;
        }
    }
    printf(" Select Option ,%d \n",position);
    int x = position;
    int a;
    int b;

    switch (x){
        case 1:
            sinus();
            Sincostan();
            break;
        case 2:
            cosinus();
            Sincostan();
            break;
        case 3:
            tangen();
            Sincostan();
            break;
        case 4:
            main();
            break;

    }
}

void sinus(){
    int pilih;
    rara:
    system("cls");
    co();
    float t;
    gotoxy(50,7);printf("MENGHITUNG SINUS");
    gotoxy(45,10);printf("Masukkan derajat sinus = ");
    scanf("%f",&t);
    float degress=PI/180;
    float sin_value=sin(t*degress);
    gotoxy(45,11);printf("nilai sinus adalah %.2f\n",sin_value);
    gotoxy(45,15);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Sinus(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        Sincostan();
    }
    else{
        system("cls");
        goto temp;
    }
}

void cosinus(){
    int pilih;
    rara:
    system("cls");
    co();
    float a;
    gotoxy(50,7);printf("MENGHITUNG COSINUS");
    gotoxy(45,10);printf("Masukkan derajat cosinus = ");
    scanf("%f",&a);
    float degress=PI/180;
    float cos_value=cos(a*degress);
    gotoxy(45,11);printf("nilai cosinus adalah %.2f\n",cos_value);
    gotoxy(45,15);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang cosinus(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        Sincostan();
    }
    else{
        system("cls");
        goto temp;
    }
}
void tangen(){
    int pilih;
    rara:
    system("cls");
    co();
    float r,a;
    gotoxy(50,7);printf("MENGHITUNG TANGEN");
    gotoxy(45,10);printf("Masukkan derajat tangen = ");
    scanf("%f",&r);
    float degress=PI/180;
    float tan_value=tanh(r*degress);
    gotoxy(45,11);printf("nilai tangen adalah %.2f\n",tan_value);
    gotoxy(45,15);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Tangen(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        Sincostan();
    }
    else{
        system("cls");
        goto temp;
    }
}

void hitkellu()
{
    system("cls");
    system("COLOR F9");
    cover();
    int position = 1;
    int keyPressed = 0;
    int maxoption = 3;
    gotoxy(51,10);
    printf("Hitung Keliling Luas");
    while(keyPressed != 13){
        gotoxy(44,14);
        arrowhere(1,position); printf(" 1. Keliling Bangun Datar");
        gotoxy(44,15);
        arrowhere(2,position); printf(" 2. Hitung Luas Bangun Datar");
        gotoxy(44,16);
        arrowhere(3,position); printf(" 3. Hitung Volume Bangun Ruang");
        gotoxy(44,17);
        arrowhere(4,position); printf(" 4. Return Menu Utama");
        keyPressed = getch();
        if(keyPressed == 80 && position !=4){
            position++;
        }else if(keyPressed == 72 && position !=1){
            position--;
        }else{
            position = position;
        }
    }
    printf(" Select Option ,%d \n",position);
    int x = position;
    int a;
    int b;

    switch (x){
        case 1:
            kel();
            hitkellu();
            break;
        case 2:
            lu();
            hitkellu();
            break;
        case 3:
            vol();
            hitkellu();
            break;
        case 4:
            main();
            break;
    }
}

void kel(){
    system("cls");
    system("COLOR F9");
    cover();
    int position = 1;
    int keyPressed = 0;
    int maxoption = 3;
    gotoxy(50,10);
    printf("Keliling Bangun Datar");
    while(keyPressed != 13){
        gotoxy(45,14);
        arrowhere(1,position); printf(" 1. Keliling Persegi Panjang");
        gotoxy(45,15);
        arrowhere(2,position); printf(" 2. Keliling Trapesium");
        gotoxy(45,16);
        arrowhere(3,position); printf(" 3. Keliling Layang-Layang");
        gotoxy(45,17);
        arrowhere(4,position); printf(" 4. Keliling Lingkaran");
        gotoxy(45,18);
        arrowhere(5,position); printf(" 5. Back");
        keyPressed = getch();
        if(keyPressed == 80 && position !=5){
            position++;
        }else if(keyPressed == 72 && position !=1){
            position--;
        }else{
            position = position;
        }
    }
    printf(" Select Option ,%d \n",position);
    int x = position;
    int a;
    int b;

    switch (x){
        case 1:
            _();
            kel();
            break;
        case 2:
            __();
            kel();
            break;
        case 3:
            ___();
            kel();
            break;
        case 4:
            ____();
            kel();
            break;
        case 5:
            hitkellu();
            break;
    }
}
void _(){
    int pilih;
    rara:
    system("cls");
    co();
    float t,i,a;
    gotoxy(45,7);printf("MENGHITUNG KELIING PERSEGI PANJANG");
    gotoxy(22,10);printf("Masukkan Panjang Persegi Panjang= ");
    scanf("%f",&t);
    gotoxy(22,11);printf("Masukkan Lebar Persegi Panjang= ");
    scanf("%f",&i);
    a= 2*(t+i);
    gotoxy(22,13);printf("Keliling Persegi Panjang adalah %.2f",a);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Keliling Persegi(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        kel();
    }
    else{
        system("cls");
        goto temp;
    }
}
void __(){
    int pilih;
    rara:
    system("cls");
    float a,l,x,n;
    co();
    gotoxy(45,7);printf("MENGHITUNG KELILING TRAPESIUM");
    gotoxy(22,10);printf("Masukkan Sisi Atas Trapesium Sama Kaki = ");
    scanf("%f",&a);
    gotoxy(22,11);printf("Masukkan Sisi Bawah Trapesium Sama Kaki= ");
    scanf("%f",&l);
    gotoxy(22,12);printf("Masukkan Sisi Miring Trapesium Sama Kaki= ");
    scanf("%f",&x);
    n= a+l+(x*2);
    gotoxy(22,14);printf("Keliling Trapesium Sama Kaki adalah %.2f",n);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Keliling Trapesium(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        kel();
    }
    else{
        system("cls");
        goto temp;
    }
}

void ___(){
    int pilih;
    rara:
    system("cls");
    float d,r,n;
    co();
    gotoxy(45,7);printf("MENGHITUNG KELILING LAYANG - LAYANG");
    gotoxy(22,10);printf("Masukkan Panjang Sisi Atas = ");
    scanf("%f",&d);
    gotoxy(22,11);printf("Masukkan Panjang Sisi Bawah = ");
    scanf("%f",&r);
    n= (d*2)+(r*2);
    gotoxy(22,13);printf("Keliling Layang-Layang adalah %.2f",n);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Keliling Layang-Layang(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        kel();
    }
    else{
        system("cls");
        goto temp;
    }
}

void ____(){
    int pilih;
    rara:
    system("cls");
    float t,i,r,a;
    co();
    gotoxy(45,7);printf("MENGHITUNG KELILING LINGKARAN");
    gotoxy(22,10);printf("Masukkan Panjang Diameter = ");
    scanf("%f",&r);
    gotoxy(22,11);printf("Masukkan Panjang Jari-Jari = ");
    scanf("%f",&a);
    t=2*PI*a;
    i=PI*r;
    gotoxy(22,13);printf("Keliling Lingkaran Berdasarkan Jari-Jari adalah %.2f\n",t);
    gotoxy(22,14);printf("Keliling Lingkaran Berdasarkan Diameter adalah %.2f",i);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Keliling Lingkaran(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        kel();
    }
    else{
        system("cls");
        goto temp;
    }
}

void lu(){
    system("cls");
    system("COLOR F9");
    cover();
    int position = 1;
    int keyPressed = 0;
    int maxoption = 3;
    gotoxy(52,10);
    printf("Luas Bangun Datar");
    while(keyPressed != 13){
        gotoxy(46,14);
        arrowhere(1,position); printf(" 1. Luas Persegi Panjang");
        gotoxy(46,15);
        arrowhere(2,position); printf(" 2. Luas Trapesium");
        gotoxy(46,16);
        arrowhere(3,position); printf(" 3. Luas Layang-Layang");
        gotoxy(46,17);
        arrowhere(4,position); printf(" 4. Luas Lingkaran");
        gotoxy(46,18);
        arrowhere(5,position); printf(" 5. Back");
        keyPressed = getch();
        if(keyPressed == 80 && position !=5){
            position++;
        }else if(keyPressed == 72 && position !=1){
            position--;
        }else{
            position = position;
        }
    }
    printf(" Select Option ,%d \n",position);
    int x = position;
    int a;
    int b;

    switch (x){
        case 1:
            l();
            lu();
            break;
        case 2:
            ll();
            lu();
            break;
        case 3:
            lll();
            lu();
            break;
        case 4:
            llll();
            lu();
            break;
        case 5:
            hitkellu();
            break;
    }
}
void l(){
    int pilih;
    rara:
    system("cls");
    float t,i,r;
    co();
    gotoxy(45,7);printf("MENGHITUNG LUAS PERSEGI PANJANG");
    gotoxy(22,10);printf("Masukkan Panjang Persegi Panjang = ");
    scanf("%f",&t);
    gotoxy(22,11);printf("Masukkan Lebar Persegi Panjang = ");
    scanf("%f",&i);
    r= t*i;
    gotoxy(22,13);printf("Luas Persegi Panjang adalah %.2f",r);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Luas Persegi Panjang(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        lu();
    }
    else{
        system("cls");
        goto temp;
    }
}
void ll(){
    int pilih;
    rara:
    system("cls");
    float t,i,r,a;
    co();
    gotoxy(45,7);printf("MENGHITUNG LUAS TRAPESIUM");
    gotoxy(22,10);printf("Masukkan Sisi Atas Trapesium Sama Kaki = ");
    scanf("%f",&t);
    gotoxy(22,11);printf("Masukkan Sisi Bawah Trapesium Sama Kaki= ");
    scanf("%f",&i);
    gotoxy(22,12);printf("Masukkan Tinggi Trapesium Sama Kaki= ");
    scanf("%f",&r);
    a= (r*(t+i))/2;
    gotoxy(22,14);printf("Luas Trapesium Sama Kaki adalah %.2f",a);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Luas Trapesium(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        lu();
    }
    else{
        system("cls");
        goto temp;
    }
}

void lll(){
    int pilih;
    rara:
    system("cls");
    float t,i,r;
    co();
    gotoxy(45,7);printf("MENGHITUNG LUAS LAYANG - LAYANG");
    gotoxy(22,10);printf("Masukkan Diagonal Panjang = ");
    scanf("%f",&t);
    gotoxy(22,11);printf("Masukkan Diagonal Lebar = ");
    scanf("%f",&i);
    r= (t*i)/2;
    gotoxy(22,13);printf("Luas Layang-Layang adalah %.2f",r);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Luas Layang-Layang(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        lu();
    }
    else{
        system("cls");
        goto temp;
    }
}

void llll(){
    int pilih;
    rara:
    system("cls");
    float t,i,r,a;
    co();
    gotoxy(45,7);printf("MENGHITUNG LUAS LINGKARAN");
    gotoxy(22,10);printf("Masukkan Panjang Diameter = ");
    scanf("%f",&t);
    gotoxy(22,11);printf("Masukkan Panjang Jari-Jari = ");
    scanf("%f",&i);
    r= (PI*(i*i));
    a= (PI*(t*t)*0.25);
    gotoxy(22,13);printf("Luas Lingkaran berdasarkan Jari-Jari adalah %.2f",r);
    gotoxy(22,14);printf("Luas Lingkaran berdasarkan Diameter adalah %.2f",a);
    gotoxy(67,20);
    printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Luas Lingkaran(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        lu();
    }
    else{
        system("cls");
        goto temp;
    }
}

void vol(){
    system("cls");
    system("COLOR F9");
    cover();
    int position = 1;
    int keyPressed = 0;
    int maxoption = 3;
    gotoxy(52,10);
    printf("Volume Bangun Ruang");
    while(keyPressed != 13){
        gotoxy(48,14);
        arrowhere(1,position); printf(" 1. Volume Kubus");
        gotoxy(48,15);
        arrowhere(2,position); printf(" 2. Volume Prisma");
        gotoxy(48,16);
        arrowhere(3,position); printf(" 3. Volume Limas");
        gotoxy(48,17);
        arrowhere(4,position); printf(" 4. Volume Bola");
        gotoxy(48,18);
        arrowhere(5,position); printf(" 5. Back");
        keyPressed = getch();
        if(keyPressed == 80 && position !=5){
            position++;
        }else if(keyPressed == 72 && position !=1){
            position--;
        }else{
            position = position;
        }
    }
    printf(" Select Option ,%d \n",position);
    int x = position;
    int a;
    int b;

    switch (x){
        case 1:
            v();
            vol();
            break;
        case 2:
            vv();
            vol();
            break;
        case 3:
            vvv();
            vol();
            break;
        case 4:
            vvvv();
            vol();
            break;
        case 5:
            hitkellu();
            break;
    }
}
void v(){
    int pilih;
    rara:
    system("cls");
    float t,i;
    co();
    gotoxy(45,7);printf("MENGHITUNG VOLUME KUBUS");
    gotoxy(22,10);printf("Masukkan Panjang Sisi Kubus = ");
    scanf("%f",&t);
    i=t*t*t;
    gotoxy(22,11);printf("Volume Kubus adalah = %.2f",i);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Volume Kubus(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        vol();
    }
    else{
        system("cls");
        goto temp;
    }
}
void vv(){
    int pilih;
    rara:
    system("cls");
    float t,i,r,a,l,x,y,z,n,v;
    co();
    gotoxy(45,7);printf("MENGHITUNG VOLUME PRISMA");
    gotoxy(22,9);printf("Masukkan Sisi Persegi = ");
    scanf("%f",&t);
    gotoxy(22,10);printf("Masukkan Lebar Alas Segitiga = ");
    scanf("%f",&i);
    gotoxy(22,11);printf("Masukkan tinggi Segitiga = ");
    scanf("%f",&r);
    gotoxy(22,12);printf("Masukkan Jari-Jari Lingkaran = ");
    scanf("%f",&a);
    gotoxy(22,13);printf("Masukkan Diameter Lingkaran = ");
    scanf("%f",&l);
    gotoxy(22,14);printf("Masukkan Tinggi Prisma = ");
    scanf("%f",&x);
    y=(t*t)*x;
    z=(i*r*x)/2;
    n=(22*a*a*x)/7;
    v=(l*l)*x*PI/4;
    gotoxy(22,16);printf("Volume Prisma Persegi adalah = %.2f\n",y);
    gotoxy(22,17);printf("Volume Prisma Segitiga adalah = %.2f\n",z);
    gotoxy(22,18);printf("Volume Silinder berdasar Jari - Jari adalah = %.2f\n",n);
    gotoxy(22,19);printf("Volume Silinder berdasar Diameter adalah = %.2f\n",v);
    gotoxy(67,21);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Volume Prisma(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        vol();
    }
    else{
        system("cls");
        goto temp;
    }
}
void vvv(){
    int pilih;
    rara:
    system("cls");
    float t,i,r,a,l,x,y,z,n,v,la;
    co();
    gotoxy(45,7);printf("MENGHITUNG VOLUME LIMAS");
    gotoxy(22,9);printf("Masukkan Sisi Persegi = ");
    scanf("%f",&t);
    gotoxy(22,10);printf("Masukkan Lebar Alas Segitiga = ");
    scanf("%f",&i);
    gotoxy(22,11);printf("Masukkan tinggi Segitiga = ");
    scanf("%f",&r);
    gotoxy(22,12);printf("Masukkan Jari-Jari Lingkaran = ");
    scanf("%f",&a);
    gotoxy(22,13);printf("Masukkan Diameter Lingkaran = ");
    scanf("%f",&l);
    gotoxy(22,14);printf("Masukkan Tinggi Limas = ");
    scanf("%f",&x);
    la=((i*r)*0.5);
    y=(t*t)*x*0.33;
    z=la*x*0.33;
    n=PHI*a*a*x*0.33;
    v=(PHI*l*x);
    gotoxy(22,16);printf("Volume Limas Persegi adalah = %.2f",y);
    gotoxy(22,17);printf("Volume Limas Segitiga adalah = %.2f",z);
    gotoxy(22,18);printf("Volume Limas Silinder berdasarkan Jari - Jari adalah = %.2f",n);
    gotoxy(22,19);printf("Volume Limas Silinder berdasarkan Diameter adalah = %.2f",v);
    gotoxy(67,21);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Volume Limas(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        vol();
    }
    else{
        system("cls");
        goto temp;
    }
}
void vvvv(){
    int pilih;
    rara:
    system("cls");
    float t,i,r,a;
    co();
    gotoxy(45,7);printf("MENGHITUNG VOLUME BOLA");
    gotoxy(22,10);printf("Masukkan Jari-Jari Lingkaran = ");
    scanf("%f",&t);
    gotoxy(22,11);printf("Masukkan Diameter Lingkaran = ");
    scanf("%f",&i);
    r = t *t * t *4/3*PI;
    a = ((PI*i*i*i)/6);
    gotoxy(22,13);printf("Volume Bola berdasarkan Jari-Jari adalah %.2f\n",r);
    gotoxy(22,14);printf("Volume Bola berdasarkan Diameter adalah %.2f\n",a);
    gotoxy(67,20);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Volume Bola(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        vol();
    }
    else{
        system("cls");
        goto temp;
    }
}

void hitakua(){
    int pilih;
    rara:
    system("cls");
    co();
    float t,i;
    gotoxy(48,8);printf("MENGHITUNG AKAR KUADRAT");
    gotoxy (42,11);printf("Masukkan Bilangan yang akan Diakar = ");
    scanf("%f",&t);
    i= sqrt(t);
    gotoxy(44,12);printf("Hasil akar dari %.2f adalah %.2f",t,i);
    gotoxy(45,15);printf("");
    system("pause");
    system("cls");
    temp:
    co();
    gotoxy(22,12);printf("Apakah anda ingin Mengulang Akar Kuadrat(y/n)?");
    scanf("%C",&pilih);
    if (pilih=='y'){
        goto rara;
    }
    else if(pilih=='n'){
        main();
    }
    else{
        system("cls");
        goto temp;
    }
}

void cover(){
    int i;
    for (i=42;i<=78;i++){
        gotoxy(i,8);
        printf("%c",178);
    }
    for (i=42;i<=78;i++){
        gotoxy(i,20);
        printf("%c",178);
    }
    for (i=42;i<=78;i++){
        gotoxy(i,12);
        printf("%c",178);
    }
    for (i=8;i<=20;i++){
        gotoxy(42,i);
        printf("%c",178);
    }
    for (i=8;i<=20;i++){
        gotoxy(78,i);
        printf("%c",178);
    }
}

void co(){
    int i;
    for (i=20;i<=100;i++){
        gotoxy(i,5);
        printf("%c",219);
    }
    for (i=20;i<=100;i++){
        gotoxy(i,22);
        printf("%c",219);
    }
    for (i=5;i<=21;i++){
        gotoxy(20,i);
        printf("%c",219);
    }
    for (i=5;i<=21;i++){
        gotoxy(100,i);
        printf("%c",219);
    }
}

void arrowhere (int realposition,int arrowposition){
    if(realposition == arrowposition){
        printf("==>");
    }else{
        printf("   ");
    }
}
