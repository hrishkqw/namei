// prime number
#include <iostream>
using namespace std;

int main(){
    int n;
cout<<"enter number ";
cin>>n;
bool flag=0;

for(int i=2;i<n;i++){
    if(n%i==0){
        cout<<"not prime number"<<endl;
        flag=1;
        break;
       }}
       
       
           if(flag==0){
       cout<<"it is prime number ";}

  return 0;
}
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\
\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\

// rever a number
#include <iostream>
using namespace std;

int main() {
int num;
cout<<"enter a number ";
cin>>num;
int rev=0; 
while(num>0){
    
    int a= num%10;
    rev= rev*10 + a;
    num=num/10;
}
cout<<rev<<endl;
 return 0;   
}
