# MZidan-IF-B
# Ujian Akhir Semester 
<br>Mata Kuliah 	: Dasar Program
<br> Nama		: MUHAMAD ZIDAN
<br>NIM		:	1227050079
<br>Jurusan		:[Teknik Informatika](http://if.uinsgd.ac.id/) [UIN Sunan Gunung Djati Bandung](https://uinsgd.ac.id/) 

## Deskripsi Umum
PROGRAM KOLOM DAN BARIS BANYAK DATA DITUKAR
## Source Code

```
#include <iostream>

using namespace std;

int main(){
	int m [100][100];
	int bris,klom,x,y;
	
	cout<<"=====================_Program Kolom dan Baris_====================="<<endl;
	cout<<"TUGAS UAS DASAR PROGRAM"<<endl;
	cout<<"Nama : Muhamad Zidan"<<endl;
	cout<<"Nim : 1227050079"<<endl;
	cout<<"==================================================================="<<endl;
	
	cout<<"Masukan nilai baris :";
	cin>>bris;
	
	cout<<"Masukan nilai kolom :";
	cin>>klom;
	
	for(x=0; x<bris; x++){
		for(y=0; y<klom; y++){
			cout<<" Baris "<<x+1<<" kolom - "<<y+1<<" : ";
			cin>>m[x][y];
		}
		cout<<endl;
	}
	
	cout<<" Hasil "<<endl;
	
	for(x=0; x<klom; x++){
		for(y=0; y<bris; y++){
			cout<<m[y][x]<<"  ";
		}
		cout<<endl;
	}
	
	cout<<" Hasil Trasnspose "<<endl;
	for(x=0; x<bris; x++){
		for(y=0; y<klom; y++){
			cout<<" "<<m[x][y];
		}
		cout<<endl;
	}
	
	return 0 ;
}
```

## Output

```
=====================_Program Kolom dan Baris_=====================
TUGAS UAS DASAR PROGRAM
Nama : Muhamad Zidan
Nim : 1227050079
===================================================================
Masukan nilai baris : 3
Masukan nilai kolom : 2
 Baris 1 kolom - 1 : 2
 Baris 1 kolom - 2 : 3

 Baris 2 kolom - 1 : 4
 Baris 2 kolom - 2 : 5

 Baris 3 kolom - 1 : 6
 Baris 3 kolom - 2 : 7

 Hasil
2  4  6
3  5  7
 Hasil Trasnspose
 2 3
 4 5
 6 7
 ```
 
