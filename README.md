//# hello-world
//my first project for github
#include<iostream>
using namespace std;
  void one(int n);
  int f(int n);
  int main(){
    cout<<"my first project"<<endl;
    return 0;
  }
  void one(int n){
    for(int i=0;i<n;i++){
      cout<<i<<endl;
    }
  }
  bool f(int n){
    for(int i=2;i*i<n;i++){
      if(n%i==0){
        return false;
      }
    }
    return true;
  }
