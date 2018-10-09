# praktikum1

##latihan1.cpp : Program menghitung luas persegi panjang

*Alur algoritma*

1. mendeklerasikan variable int `A, T` sebagai variable input
2. mengisi nilai variable input dengan nilai tertentu, misal: `A = `dan `T = `
3. menghitung luas dengan rumus `L = A * T`
4. mencetak hasil kelayar. `cout << L << endl;`

*berikut code lengkapnya:*

#include <iostream>

using namespace std;

int main(){
int p,l,keliling;
cout<<"masukan panjjang persegi panjang: ";
cin>>p;
cout<<"masukan lebar persegi panjang: ";
cin>>l;

keliling=p+l+p+l;
cout<<"keliling persegi panjang adalah " <<keliling;
return 0;

}
