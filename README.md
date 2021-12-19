# Show-Divisibility

#include <iostream>
#include <conio.h>
using namespace std;
int main()

{
	int a , b;
	cout<<"Please Enter two positive Number:"<<endl;
	cout<<"Enter Number a:"<<endl;
	cin>>a;
	cout<<"Enter Number b:"<<endl;
	cin>>b;
	
	if (a%b) cout<<a<<"  is not divisible by  "<<b<<endl;
	else cout<<a<<"  is divisible  by  "<<b<<endl;
	
	getch();
}
