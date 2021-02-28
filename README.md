# calculater-making-with-if-else-if
#include<iostream>
#include<math.h>
using namespace std;
int main()

{
		//how to make calculater with c++ programm using if else if statement
	float num1,num2;
	char op;
	cout<<"enter your first number for calculating";
	cin>>num1;
	cout<<"Enter opperater";
	cin>>op;
		cout<<"enter your 2nd number for calculating";
		cin>>num2;
		if(op=='+'){
			cout<<num1+num2;
			
		}
		else if(op=='-'){
				cout<<num1-num2;
			
		}
		else if(op=='*'){
				cout<<num1*num2;
			
		}
		
	//	else if(op=='%'){
		//		cout<<num1%num2;
			
	//	}
		else
		cout<<"you enter a wrong operater";

	
/*
	//how to make calculater with c++ programm using switch statement
	float num1,num2;
	char op;
	cout<<"enter your first number for calculating";
	cin>>num1;
	cout<<"Enter opperater";
	cin>>op;
		cout<<"enter your 2nd number for calculating";
		cin>>num2;
	switch(op)
	{
		case '+':
		cout<<num1+num2;
		break;
		case '-':
		cout<<num1-num2;
		break;
		case '*':
		cout<<num1*num2;
		break;
		case '/':
		cout<<num1/num2;
		break;
	//	case '%':
	//	cout<<num1%num2;
	//	break;
		default:
			cout<<"error! opperater is not connect";
		
	}
  return 0;
  }
