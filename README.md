//# power-of-number
//write a program to find x to the power n(i.e x^n) Take x and n from the user. you need to print the answer
#include<math.h>
#include<iostream>
using namespace std;

   int main() {
	// Write your code here
	
        int x, n, power;
       cin>>x;
       cin>>n;
       
       power=pow(x,n) ;
       cout<<power;
}
