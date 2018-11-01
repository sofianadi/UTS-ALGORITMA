#Tugas UTS
##soal1.cpp

**Alur Argoritma** 
1. Deklarasikan Variabel A, B, X, Y, sebagai variabel input.
2. Membaca input keyboard cin >> A >> B >> X >> Y.
3. Membandingkan Variabel X dengan Y jika Sama.
4. Karena statement **false** tidak akan terjadi karena ''' {X!=Y}'''.
5. Dan jika statement **true** maka X < Y berlaku rumus statement **true** dengan Syntax ''' X = X + A'''.
6. dan jika statement **False**a''' Y = Y + B'''.
7. Maka akan muncul ''' X = X + A = (Hasilnya)'''.

**Code Program**
'''c++
#include <iostream>

using namespace std;

int main ()
{
    int A, B, X, Y;

    cout << "masukkan bilangan 1: ";
    cin >> A;
    cout << "masukkan bilangan 2: ";
    cin >> B;

    X = A;
    Y = B;
    if(X != Y )
        {if ( X < Y)
            { X = X + A;}
        else
            { Y = Y + B;}
        }
    cout << X;
}
'''
**Hasil**
![img] (https://raw.githubusercontent.com/sofianadi/UTS-ALGORITMA/master/SSsoal1A.png)
![img] (https://raw.githubusercontent.com/sofianadi/UTS-ALGORITMA/master/SSsoal1B.png)

##soal2.cpp
1. deklarasi varaible input N,X,T, Batas;
sebagai inputnya
2. memasukan nilai N yaitu 2 angka terakhir saya, maka N dalah 56
dan batasnya adalah 196 dari hasil jumlah N + 140,.
3. masukan variable X, dan T, X nya adalah 20 dan kemudian T adalah 78(dari N).
4. dimana T kurang dari sama dengan batas, berarti tidak boleh melebihi batas 
5. kemudian menghitung ```X = X + 10;
```,dan hasinya 30 kemudian menghitung ```
T = T + X;```,
hasilnya adalah 86.
6. kemudian cetak variable T 

**Code Program**

```c++

#include<iostream>
#include <math.h>
using namespace std;

int main()
{
    int N,X,T,Batas;
    cout << "masukan nilai N dengan dua NIM terakhir : " ; cin >> N ;
    Batas = N + 100;
    X = 20;
    T = N;
    while( T <= Batas)
{ T = T + X;
X = X + 10;
}
cout <<"hasilnya adalah :" << T <<endl;
}
'''
**hasil**
![img](https://raw.githubusercontent.com/sofianadi/UTS-ALGORITMA/master/SSsoal2.png)