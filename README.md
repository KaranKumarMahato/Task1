# Task1
This task is basically about  a simple calculator
#include<iostream>
using namespace std;
int main(){
    int a,b;
    cout << "Enter the first number"  << endl;
    cin >>  a;
    cout << "Enter the second number" << endl;
    cin >> b;
    char ch;
    cout << "enter which operation do you want to perform:" ;
    cin >> ch;
    switch(ch){
        case '+':{cout << (a+b) << endl;
                  break;}
        case '-':{cout << (a-b) << endl;
                  break;}
        case '*':{cout << (a*b) << endl;
                  break;}
        case '/':{cout << (a/b) << endl;
                  break;}
    }
    return 0;
}
