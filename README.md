# Theme-park
#include<iostream>
using namespace std;
int main()
{
	float height;  //declaring variable with datatype float
	int age;       //declaring variable with datatype int
	cout << "Enter your age " << endl;
	cin >> age;
	cout << "Enter your height " << endl;
	cin >> height;
	if (height >= 0.6 && age >= 5)  //using if else statement to check if the user can ride or not.
	{
		cout<<"You are allowed to ride! " << endl;  //if height is greater than or equal to 0.6 and age is greater than or equal to 5 then if block of statements will be displayed
	}
	else {                                        //if the userinput does not satisfy if condition then the statements within else will be displayed 
		cout << "You are not eligible to ride " << endl;
	}
	return 0;
}
