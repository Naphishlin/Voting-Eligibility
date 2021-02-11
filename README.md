#include<iostream>
using namespace std;

int main() 
{
    int age;
    cout << "Enter age of a user:\n";
    cin>>age;
    //person is teenager or not
	//>=13 and <=19
	if(age>=13 && age<=19)
	{
		cout<<"Person is Teenager\n";
	}
	else
	{
		cout<<"Person is not a Teenager\n";
	}
	//condition to check voting eligility
	if (age >= 18) 
	{
        cout << "Congratulation!You are eligible for voting\n";
    }
	 else 
	{
        cout << "You are not eligible for voting \n";
        cout << "You would be able to caste your vote after " << 18-age << " year" ;
    }

    return 0;
}
