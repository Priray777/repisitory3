@latihan1

#include <iostream>

int main()
{
	int i= 0;
	int max= 0;
	int a,x;

	std::cout << "masukan jumlah bilangan : ";
	std::cin >> a;

	for (i;i<a;i++)
	{
		std::cout << "masukan bilangan ke - " << i+1 << ": " ;
		std::cin >> x;
		if (x>max)
			max=x;
	}

	std::cout << "bilangan terbesarnya adalah : " << max;
	return 0;
}




![alt text](https://github.com/Priray777/repisitory3/blob/master/latihan1.png)



@latihan2

#include <iostream>

using namespace std;
int main()
{
	int a,b,c;

	cout << "masukan nilai pertama : ";
	cin >> a ;
	cout << "masukan nilai kedua : ";
	cin >> b ;
	cout << "masukan nilai ketiga : ";
	cin >> c ;



	if (a<b){
		if (b<c)
		cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : " 
		<< a << " "<< b << " " <<c ;
		else{
			if (a<c)
				cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : "
				<< a << " "<< c << " " <<b ;
			else
				cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : " 
				<< c << " "<< a << " " <<b ;
		}
	}

	else
	{
		if (a<c)
			cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : " 
			<< b << " "<< a << " " <<c ;
		else
		{
			if(b<c)
			cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : " 
			<< b << " "<< c << " " <<a;
			else
			cout << "urutan dari nilai yang terkecil sampai terbesarnya adalah : " 
			<< c << " "<< b << " " <<a ;
		}
	}

	
	return 0;
}

![alt text](https://github.com/Priray777/repisitory3/blob/master/latihan2.png)



@latihan3


#include <iostream>

using namespace std;
int main()
{
	int a,b,c;

	cout << " masukan nilai pertama : ";
	cin >> a ;
	cout << " masukan nilai kedua : ";
	cin >> b ;
	cout << " masukan nilai ketiga : ";
	cin >> c ; 


	if (a<b){
		if (b<c)
		cout << "nilai tengahnya adalah : "<< b ;
		else{
			if (a<c)
				cout << "nilai tengahnya adalah : "<<  c ;
			else
				cout << "nilai tengahnya adalah : "<< a ;
		}
	}

	else
	{
		if (a<c)
			cout << "nilai tengahnya adalah : "<< a ;
		else
		{
			if(b<c)
			cout << "nilai tengahnya adalah : "<< c ;
			else
			cout << "nilai tengahnya adalah : "<< b ;
		}
	}

	
	return 0;
}

![alt text](https://github.com/Priray777/repisitory3/blob/master/latihan3.png)