# Vector-Declaration-Exercise
A look into how to declare vectors in c++

## Description(Detailed)
  Greetings! you may be wondering why I made this. To put it simply, I made this very basic vector code because I had spent all my time searching up how to make vectors in c++ BUT never actually had hands on experience...Until now. this is just a primer for me, look at this in terms of me showing that I can write a vector  declaration in c++. I plan to post more content like this up on my github so people can see what I am up to. Upon getting more experience I will post more content that is focuesd on Unity c# and Unreal engine 4 C++. Until then this is what I have to show to demonstrate my understanding/experience with c++.
  
  
## Disclaimer
  This isn't the first time I have posted c++ on here. The FIRST major project for c++ that I have is an OpenGL c++ program that aims to change the background color of a given window, draw with the mouse inside of a given window and many more. this exercise that I am posting right now is to show that I can demonstrate how to declare variables, vectors, push vector values into an empty vector, classes and many more fundamental c++ concepts. Once I found that I am comfortable to write more complex systems I will update my github with more complex game projects/concepts. It won't be instant and will take some time but in the end it will be worth it.
  
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
