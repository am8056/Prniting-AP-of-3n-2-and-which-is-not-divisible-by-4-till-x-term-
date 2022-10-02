# Prniting-AP-of-3n-2-and-which-is-not-divisible-by-4-till-x-term-

#include<iostream>
using namespace std;
int main(){
    int n;
    cin>>n;
 int temp=0;
    for(int i=1;i<=n;i++){
   		temp=3*i+2;
        if(temp%4!=0){
        cout<<temp<<" ";}
        else
            n++;         // n++ will increase the value of n in loop so we can print n term only
    
    }
}
