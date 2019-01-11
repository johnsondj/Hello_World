# Hello_World
My First Repository
// Just learning how to write code and practicing how to use GitHub.

// Basic calculator
#include "stdafx.h"
#include <iostream>

using namespace std;

double add(double a, double b); // function declarations
double subtract(double a, double b);
double multiply(double a, double b);
double divide(double a, double b);

int main()
{
	double a, b;
	cout << "A program that adds, subtracts, multiplies, and divides the value of two digits." << endl;
	cout << "\nEnter A: ";
	cin >> a;
	cout << "\nEnter B: ";
	cin >> b;
	cout << "\nAddition of " << a << " + " << b << " = " << add(a, b) << endl;
	cout << "Subtraction of " << a << " - " << b << " = " << subtract(a, b) << endl;
	cout << "Multiply " << a << " * " << b << " = " << multiply(a, b) << endl;
	cout << "Divide " << a << " by " << b << " = " << divide(a, b) << endl;
	cout << endl;
	
	system("pause");

	return 0;
}

double add(double a, double b) { // function definitions
	return a + b;
};

double subtract(double a, double b) {
	return a - b;
};

double multiply(double a, double b) {
	return a * b;
};

double divide(double a, double b) {
	return a / b;
};
	

