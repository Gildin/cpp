#include<iostream>
#include<cstdio>

using namespace std;
int main(int argc, char *argv[])
{
	//kalkulator by Gildin
	menu:
	printf("Menu\n1.Dodawanie\n2.Odejmowanie\n3.Dzielenie\n4.Mnozenie\n");
	int liczby[2];
	int chose;
	int wynik;
	cin>>chose;
	
    printf("\nprowadz 2 liczby\n");
    
    cin>>liczby[0];
    printf("I kolejna liczba\n");
    cin>>liczby[1];
    system("cls");
    
    switch(chose)
    {
    	case 1:
    	wynik =liczby[0]+liczby[1];
    	break;
    	case 2:
    	wynik= liczby[0]-liczby[1];
    	break;
    	case 3:
    	wynik=liczby[0]%liczby[1];
    	break;
    	case 4:
    	wynik = liczby[0]*liczby[1];
    	break;
    	
    }
    printf("\nwynik:%d\nwpisz 1 aby wrocic do menu\nwpisz 2 aby wyjsc\n",wynik);
    int z;
    cin>>z;
    switch(z)
    {
    	case 1:
    	goto menu;
    	break;
    	case 2:
    	system("exit");
    	break;
    }
    system("cls");
    
}
