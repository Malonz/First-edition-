# First-edition-
Hey  those lines of code using C++ was actually my first project using this language ...... in my free time  I try to learn a   new thing  ,  hope you like it  
////////////////////////////// calculator ///////////////////////////////////////////
#include <iostream>

using namespace std;

int main()
{
    int num1 , num2 , num3 ;
    int result ;
    char op;
    int result2 ;
    cout << " plz enter the first number " ;
    cin >> num1 ;
    cout << " plz enter the second number " ;
    cin >> num2 ;
    cout << " plz enter the third number " ;
    cin >> num3 ;
    cout << "plz choose which type of operation you want " ;
    cin >> op ;
  ///////////////////////// the first part calcu /////////////////////
    if ( op == '+') {
        result = num1 + num2 + num3 ;
    } else if (op == '-') {
        result = num1 - num2 - num3 ;
    }else if (op == '/') {
        result = num1 / num2 / num3 ;
    }else if (op =='*') {
        result = num1 * num2 * num3 ;
    }
    cout << "the result is " << result << endl ;
  //////////////////// second part the max number ///////////////////
   if ( num1 >= num2 && num1 >= num3 ) {
    result2 = num1 ;

 }  else if ( num2 >= num1 && num2 >= num3 ) {
    result2 = num2 ;
}  else {
    result2 = num3 ;

    }
     cout << "the  max number is  " << result2 << endl ;

    }
