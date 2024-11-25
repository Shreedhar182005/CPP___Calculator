# Calculator-In-C-using-the-Easiest-Method-of-If-and-Else.
This Calculator is made using C++ . You can take idea as well a level 1 project.

#include<iostream>
#include<cmath>
using namespace std;
int main(){
  int i;
  int a;
  int b;
  int div;
  cout<<"                  Available operation : "<<endl<<endl;
  cout<<"+---------------------------------------------------+"<<endl;
  cout<<"| 1 = Addition"<<"              |    2 = Subtraction    |"<<endl;
  cout<<"| 3 = Multiplication"<<"        |    4 = Division(Q)    |"<<endl;
  cout<<"| 5 = Division(R)"<<"           |    6 = Check odd even |"<<endl;
  cout<<"| 7 = Square"<<"                |    8 = Square root    |"<<endl;
  cout<<"| 9 = Check divisible"<<"       |    10 = palindrome    |"<<endl;
  cout<<"+---------------------------------------------------+"<<endl<<endl;
  cout<<"                 Select your Operation"<<endl;
  int choice;
  for(i=0;i<1000;i++){
    cin>>choice;
      if(choice==1){
        cout<<"Addition"<<endl;
        cout<<"Enter first number : ";
        cin>>a;
        cout<<"Enter second number : ";
        cin>>b;
        cout<<"The sum of "<<a<<" and " <<b<< " is : "<<a+b<<endl;
        cout<<"Thank you use again :) "; 
      }
     if(choice==2){
       cout<<"Substraction"<<endl;
       cout<<"Enter first number : ";
       cin>>a;
       cout<<"Enter second number : ";
       cin>>b;
       cout<<"The Diffrence of "<<a<<" and "<<b<<" is : "<<a-b<<endl;
       cout<<"Thank you use again :) "; 
     }
      if(choice==3){
        cout<<"Multiplication"<<endl;
        cout<<"Enter first number : ";
        cin>>a;
        cout<<"Enter second number : ";
        cin>>b;
        cout<<"The Product of "<<a<< " and "<<b<<" is : "<<a*b<<endl;
        cout<<"Thank you use again :) ";
      } 
      if(choice==4){
        cout<<"Division (Quotient)"<<endl;
        cout<<"Enter first number : ";
        cin>>a;
        cout<<"Enter second number : ";
        cin>>b;
        cout<<"The quotient is : "<<a/b<<endl;
        cout<<"Thank you use again :) ";    
      }
      if(choice==5){
        cout<<"Division(Remainder)"<<endl;
        cout<<"Enter first number : ";
        cin>>a;
        cout<<"Enter second number : ";
        cin>>b;
        cout<<"The Remainder(modulus) is : "<<a%b<<endl;
        cout<<"Thank you use again :) "; 
      }
      if(choice==6){
        cout<<"Odd or Even"<<endl;
        cout<<"Enter digit :";
        cin>>a;
        if(a%2==0){
          cout<<a<<"is Even number"<<endl;
          cout<<"Thank you :)"<<endl;
        }
        if(a%2!=0){
          cout<<a<<" is Odd number"<<endl;
          cout<<"Thank you :)"<<endl;
        }
        }
      if(choice==7){
        cout<<"Square"<<endl;
        cout<<"Enter digit :";
        cin>>a;
        cout<<"The square of "<<a<<" is "<<a*a<<endl;
        cout<<"Thank you :)"<<endl;
      }
      if(choice==8){
        cout<<"Square Root"<<endl;
        cout<<"Enter digit :";
        cin>>a;
        cout<<"The Square root of "<<a<<" is "<<sqrt(a)<<endl;
        cout<<"Thanks a lot use again :)"<<endl;
      }
      if(choice==9){
        cout<<"Check Divisibility"<<endl;
        cout<<"Enter value to be checked : ";
        cin>>a;
        cout<<"Enter divisibility Check number : ";
        cin>>div;
        if(a%div==0){
          cout<<a<<" is divisible by "<<div<<endl;
        }
        else{
          cout<<"not divisible"<<endl;
        }
      }
      return 0;

    }


  }



        
