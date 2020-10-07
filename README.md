# Vector-Declaration-Exercise
A look into how to declare vectors in c++

## Description(Detailed)
  Greetings! you may be wondering why I made this. To put it simply, I made this very basic vector code because I had spent all my time searching up how to make vectors in c++ BUT never actually had hands on experience...Until now. this is just a primer for me, look at this in terms of me showing that I can write a vector  declaration in c++.
  
## What this project is intended for
- Demonstrate how to properly declare a vector class
- Demonstrate how to properly push values into an empty vector via push_back()
- Demonstrate how to declare an empty vector
  
## Skills learned/Aquired
- How to declare a vector list
- Push values into an empty vector
- The use of vecctors when using them in game development
  
## Code Snippet
  
    #include "pch.h"
    #include <iostream>
    #include <Vector>

    using namespace std;



    int main()
    {
	    class somevariableName
	  {
	public:

		//vector that holds a int value
		vector<int> myintVector();		//Also Written as STD::VECTOR<INT>; when namespace is not given

		//Vector that holds a Float value
		vector<float> myfloatVector();	//vector that holds float values (STD::VECTOR<FLOAT>)

		//Vector that holds a char value
		vector<char> mycharVector();		//vector that holds char values (STD::VECTOR<CHAR>)
	};

	//Vector Declaration
	vector<int> simpleintVector;
	
	//.push_back pushes a given value into the created vector 
	simpleintVector.push_back(23);


	for (size_t i = 0; i < simpleintVector.size(); i++)
	{
		cout << simpleintVector[i] << " ";
	}
	system("PAUSE");
	return 0;
	}
