# Find-Dublicate-item-in-array-C-
#include<iostream>
using namespace std;
int main()
{
int arr[9]={0,7,2,5,4,7,1,3,6};
for(int i=0;i<9;i++)
{
	int c=0;
	for(int j=1;j<9;j++)
	{
		if(arr[i]==arr[j])
		c++;
	}
	if(c>1)
	{
		cout<<arr[i];
		return 0;
	}


}
}
