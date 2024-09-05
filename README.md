#include<iostream>
#include<string>
using namespace std;
int main()
{
	string input;
	cout<<"Enter The Any String: ";
	getline(cin,input);
	int length=input.length();
	for(int i=0;i<=length;i++){
		cout<<input[length-i];
	}
	
	return 0;
	
}
