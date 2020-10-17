# Array_C++
Created by Abdulrahim Mulla


//Array_C++
#include <iostream>
using namespace std;

int main()
{	
	int arr[5]={};
	int x;
	cout<<"\nEnter Elements : ";
	for(x=0;x<=4;x++)
	{		
	cin>>arr[x];
	}
//	cout<<"\nEnter Elements : 1\n2\n3\n4\n5\n";
	cout<<"\nYou Entered : ";
	for(x=0;x<=4;x++)
	{	
	cout<<arr[x]<<" \n ";
	
	}	
	return 0;
}
