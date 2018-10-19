# praktikum2

## latihan1.cpp : program menghitung bilangan terbesar dari 3 bilangan

**Alur Algoritma**

1. Mendeklarasikan variable `int A, B, C` sebagai variable input.
2. Membaca input dari keyboard `cin >> A >> B >> C`
3. Membandingkan nilai variable **A** dan **B**
4. Kondisi True, maka bandingkan nilai variable **A** dengan **C**
5. Kondisi False, maka bandingkan nilai variable **B** dengan **C**

**Flowchart Prgram Flowchart**
![flowchart](https://github.com/iisamelia/praktikum2/blob/master/flowchart1.png)

**code lengkap:**
```c++
#include<iostream>

using namespace std;

int main() {
    int A, B, C;
    
    cout << "Masukkan bilang 1: "; 
    cin >> A;
    
    cout << "Masukkan bilang 2: "; 
    cin >> B;
    
    cout << "Masukkan bilang 3: "; 
    cin >> C;
    
    if (A > B) {
        if (A > C) 
            cout << "Bilangan terbesar adalah: " << A << endl;
        else 
            cout << "Bilangan terbesar adalah: " << C << endl;
    } else {
        if (B > C) 
            cout << "Bilangan terbesar adalah: " << B << endl;
        else 
            cout << "Bilangan terbesar adalah: " << C << endl;
    } 
}
```

**hasilnya**

![hasilnya](https://github.com/iisamelia/praktikum2/blob/master/hasil1.PNG)


## latihan2.cpp : program menghitung bilangan terbesar dari 4 bilangan

**Alur Algoritma**

1. Mendeklarasikan variable `int A, B, C,D` sebagai variable input.
2. Membaca input dari keyboard `cin >> A >> B >> C >> D`
3. Membandingkan nilai variable **A** dan **B**
4. Kondisi True, maka bandingkan nilai variable **A** dengan **C**
5. Kondisi False, maka bandingkan nilai variable **B** dengan **C**
6. kondisi True, maka bandingkan nilai variabel **C** dengan **D**

**Flowchart Prgram Flowchart**
![flowchart](https://github.com/iisamelia/praktikum2/blob/master/flowchart2.png)

**code lengkap:**
```c++
#include<iostream>

using namespace std;

int main() {
    int A, B, C, D;

    cout << "Masukkan bilang 1: ";
    cin >> A;

    cout << "Masukkan bilang 2: ";
    cin >> B;

    cout << "Masukkan bilang 3: ";
    cin >> C;

    cout << "Masukkan bilang 4: ";
    cin >> D;

    if (A > B) {
        if (A > C)
            cout << "Bilangan terbesar adalah: " << A << endl;
        else
            cout << "Bilangan terbesar adalah: " << C << endl;
    } else {
        if (B > C)
            cout << "Bilangan terbesar adalah: " << B << endl;
        else
            cout << "Bilangan terbesar adalah: " << C << endl;
        if (D > C)
            cout << "Bilangan terbesar adalah :" << D << endl;

    }
}
```

**hasilnya**

![hasilnya](https://github.com/iisamelia/praktikum2/blob/master/hasil2.PNG)





