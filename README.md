#include <iostream>
using namespace std;

void main()
{
	char kar;             //pendefinisian variabel kar
	kar = 'A';            //penguasaan 'A' ke variabel kar

	int bil;
	bil = 32763;
	
	long jum_penduduk;
	jum_penduduk = 170123456;

	float bil_float;
	bil_float = 1.23e2;

	float a;
	double b;
	a = 56.0123456789123456789;
	b = 56.0123456789123456789;

	cout <<"isi kar                   = "<<kar<<'\n';
	kar = 66;        //penugasan nilai ASCII ke kar

	cout <<"isi kar                   = "<<kar<<'\n';
	cout <<"isi bil                   = "<<bil<<'\n';

	bil = -66;       //penugasan nilai negatif ke integer

	cout <<"isi bil                    = "<<bil<<'\n';

	cout <<"isi jum_penduduk          = "<<jum_penduduk<<'\n';
	cout <<"isi bil_float             = "<<bil_float<<'\n';

	cout <<"Isi a (float)             = "<<a<<'\n';
	cout <<"Isi b (double)            = "<<b<<'\n';
}
