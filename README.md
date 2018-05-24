# Determine-if-coordinates-are-within-the-circle
#include<iostream>  
#include<cmath>  
using namespace std;

int main()
{
	float a, b, c;
	cin >> a;
	cin >> b;
	c = a * a + b * b;
	if (sqrt(c)> 100)
		cout << "outside" << endl;
	else
		cout << "inside" << endl;
	system("pause");
}
