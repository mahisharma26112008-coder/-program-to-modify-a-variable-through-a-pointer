# -program-to-modify-a-variable-through-a-pointer

#include<iostream>
  using namespace std;  
    int main(){
        int x;
        cout<<"enter the value of x : "<<"\n";
        cin>>x;

        int *p=&x;

        cout<<"the value of x before modification : "<<x<<"\n";

        cout<<"enter the value of x for modify "<<"\n";
        cin>>*p;
        

        cout<<"the value of x after modification : "<<x<<"\n";

        return 0;
    }
