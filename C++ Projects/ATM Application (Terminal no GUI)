#include<iostream>
using namespace std;

string name = "";
double checkings = 200.00;
double savings = 1000.00;
double deposit = 0.00;
int option = 0;
double withdraw;

int main() 
{
	cout << "Welcome to Dutch && Dusty Bank, Please enter your name: "; // Welcomes the Client
	cin >> name; // Takes that name in a varible
	cout << "\n Hello! " << name << "\n"; //Prints the name back
	cout << "\n Choose one of the following options" << endl; //Asks for options
	cout << "1. Check Balance" << endl;
	cout << "2. Deposit" << endl;
	cout << "3. Withdraw" << endl;
	cout << endl;
	cout << "(Use the corresponding number to choose) Option: " << endl;
	cin >> option;

	if (option == 1) {
		int option = 0;
		cout << "For checkings account (1) For savings (2): ";
		cout << "Option: ";
		cin >> option;
		if (option == 1) {
			cout << "\n Your checkings account Balance is: $" << checkings;
		}
		if (option == 2) {
			cout << "\n Your savings account Balance is: $" << savings;
		}
	}
	if (option == 2) {
		int option = 0;
		cout << "choose the account to make a deposit";
		cout << "For checkings (1) For savings (2)" << endl;
		cout << "Option: ";
		cin >> option;
		if (option == 1) {
			cout << "enter the amount you want to deposit (checkings)" << endl;
			cout << "Amount: ";
			deposit = 0;
			cin >> deposit;
			checkings = checkings + deposit;
			cout << "Your new balance is: $" << checkings;
		}
		if (option == 2) {
			cout << "enter the amount you want to deposit (savings)" << endl;
			cout << "Amount: ";
			deposit = 0;
			cin >> deposit;
			savings = savings + deposit;
			cout << "Your new balance is: $" << savings;
		}
	}
	if (option == 3) {
		option = 0;
		cout << "Choose the account you want to withdraw from" << endl;
		cout << "for Checkings (1) for Savings (2)" << endl;
		cin >> option;
		if (option == 1) {
			cout << "How much would you like to withdraw (checkings)" << endl;
			cout << "You currently have $" << checkings << endl;
			cout << "Amount of withdraw: ";
			withdraw = 0;
			cin >> withdraw;
			if (withdraw > checkings) {
				cout << "invalid amount, you have " << checkings;
			}
			else {
				checkings = checkings - withdraw;
				cout << "Your new balance is: $" << checkings;
			}
		}
		if (option == 2) {
			cout << "How much would you like to withdraw (savings)" << endl;
			cout << "You currently have $" << savings << endl;
			cout << "Amount of withdraw: ";
			withdraw = 0;
			cin >> withdraw;
			if (withdraw > savings) {
				cout << "invalid amount, you have " << savings;
			}
			else {
				savings = savings - withdraw;
				cout << "Your new balance is: $" << savings;
			}
		}
	}
	return 0;
}

