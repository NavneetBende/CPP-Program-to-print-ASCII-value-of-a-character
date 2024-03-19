To find ASCII value of a Character in C++
Here, on this page we will discuss the program to find the ASCII value of a character in C++ .The variable of char data type can hold basically three types of characters. These characters can be differentiated on the basis of ASCII value which have been assigned to them.

ASCII value of a character in C++
While loop in C
Did you know?
 ASCII stands for American Standard Code for Information Interchange
Which is a binary code used by electronic equipment for electronic communications
A total of 128 characters have been assigned values from 0 – 127
Alphabets (  65 – 90  &  97 – 122  )
Digits (  48 – 57  )
Remaining are Special Character (  !, @, #, $, * …..)
Working
User gives an input
Input is stored in a char type variable say val.
val is converted from char to int .
The ASCII value of Character is Obtained
ASCII Value of a character
C code
Run
//C++ program to calculate ASCII value of Character
#include <iostream>
using namespace std;

//main program
int main()
{
	char val='z';

    //printing the ASCII value of input 
    //through typecasting
    cout<<"The ASCII value of "<<val<<" is "<<(int)val;
    return 0;
}
Output
The ASCII value of z is 122
