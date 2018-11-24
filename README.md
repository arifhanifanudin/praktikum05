# Latihan01

"Menginput Bilangan Sebanyak-banyaknya Sampai Angka 0"

Deklarasi Algoritma :

1. mulai program 
2. int a,max=0 
3. masukan bilangan sebanyak-banyak nya 
4. jika (a>max) 
5. max = a 
6. sementara (a!=0) 
7. cout << max 
8. cetak bilangan terbesar 
9.selesai

# program C++

#include <iostream>
  
using namespace std;

int main()

{

    int a,max=0;
    
    do{
    
    cout << "Masukan Bilangan : ";
    
    cin >> a;
    
    if (a>max)
    
        max=a;
        
    }
    
    while (a!=0);
    
    cout <<max;
    
    return 0;
    
}

# Foto Hasil
![img](https://raw.githubusercontent.com/arifhanifanudin/praktikum05/master/latihan01/hasil01.PNG)

# Latihan02

"Menginput 3 Bilangan Cetak Benar dan Salah"

1. mulai program 
2. int a,b,c 
3. masukan nilai ke 1 (a) 
4. masukan nilai ke 2 (b) 
5. masukan nilai ke 3 (c) 
6. jika (a+b=c) atau (a+c=b) cetak "Benar" 
7. jika (b+c=a) cetak "Benar" 
8. tetapi jika ( a + b !=c )cetak "Salah" 
9. selesai

# program C++

#include <iostream>
  
using namespace std;

int main (){

	int a,b,c;
  
	cout<<"masukan nilai ke 1 :";
  
	cin>>a;
  
	cout<<"masukan nilai ke 2 :";
  
	cin>>b;
  
	cout<<"masukan nilai ke 3 :";
  
	cin>>c;

	if((a+b==c)||(a+c==b))
  
	{
  
		cout<<"benar";
    
	}
  
	else if ((b+c==a))
  
	{
  
		cout<<"benar";
    
	}
  
	else
  
	{
  
		cout<<"salah";
    
	}
  
}

# Foto hasil
*Benar
![img](https://raw.githubusercontent.com/arifhanifanudin/praktikum05/master/latihan02/hasil02.PNG)
*Salah
![img](https://raw.githubusercontent.com/arifhanifanudin/praktikum05/master/latihan02/hasill2.1.PNG)

