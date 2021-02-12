# Lab-10.60
#include <iostream>
using namespace std;

int main() {
string name;
int number;

cout << "Hi, what is your name?" << endl;
cin >> name;
cout << "Pick a number between 1 and 5:" << endl;
cin >> number;

switch (number) 
{
case 1 : cout << "Greetings" << name << endl;
      break;
case 2 : cout << "How is your day?" << endl;
      break;
case 3 : cout << "Have a great day!" << endl;
      break;
case 4 : cout << "What are your plans for the day?" << endl;
      break;
case 5 : cout << "Seize the day!" << endl;
      break;
}
}
