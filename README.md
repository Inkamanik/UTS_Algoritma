# UTS_Algoritma


**Soal Pertama**

**Alur Program**
1. Deklarasikan variabel `A,B,X,Y` sebagai variabel input
2. Membaca input keyboard `cin >> A >> B >> X >> Y`
3. Membandingkan variabel **X** dengan **Y** jika sama
4. Karena statement **False** tidak akan terjadi karena `{X !=Y}`
5. Dan jika statement **True** dengan Syntax `X = X + A`
6. Dan jika statement **False** `Y = Y + B`
7. Maka akan muncul `X = X + A = (Hasilnya)`

**Code Program**
```c++
#include<iostream>

using namespace std;

int main ()
{
    int A,B,X,Y;
    cout << "Masukan bilangan 1: ";
    cin >> A;
    cout << "Masukan bilangan 2: ";
    cin >> B;

    X = A;
    Y = B;
    if(X != Y )
           {if ( X < Y )
                 { X = X + A;}
            else
                 { Y = Y +B;}
           }


    cout << X;




    }

```

hasil (a) :
![ing](https://raw.githubusercontent.com/Inkamanik/UTS_Algoritma/master/Hasil(a).png)

hasil (b) :
![ing](https://raw.githubusercontent.com/Inkamanik/UTS_Algoritma/master/Soal%201/Hasil(b).png)

**Soal Kedua**

**Alur Program**
1. Deklarasikan variabel input `N,X,T, Batas;` sebagai inputnya.
2. Masukan nilai N yaitu 2 angka terakhir NIM saya, maka N adalah 05 dan batasnya adalah 105 dari hasil penjumlahan N + 100
3. Masukan variabel X dan T. X = 20 dan T = 05 (Dari N)
4. Dimana T kurang dari sama dengan batas, berarti tidak boleh melebihi batas
5. Kemudian menghitung `X = X + 10;` dan hasilnya 30 kemudian menghitung `T = T + X;`, hasilnya adalah 35.
6. Kemudian cetak variabel T.

**Code Program**
```c++
#include<iostream>

using namespace std;

int main ()
{
     int N,X,T,Batas;

     cout << "Masukan nilai N: ";
     cin >> N;

     Batas = N + 100;
     X = 20;
     T = N;

     while ( T <= Batas)
         { T = T + X;
           X = X + 10;
         }

     cout << T;

     }

```

hasilnya :
![ing](https://raw.githubusercontent.com/Inkamanik/UTS_Algoritma/master/Soal%202/Hasil2.png)
