# Standard-Math-Library

SLIDE 3, Standard Library Math Methods

    #include <iostream>
    #include <string>
    #include <math.h>
    using namespace std;

    int main()
    {
        //pow(); power
        cout << "The cube of 8 is " << pow(8, 3) << endl; //pow (number, exponent value)

        //sqrt(); square root
        cout << "The square-root of 8 is " << sqrt(8) << endl;
        cout << "The square-root of 8 is " << pow(8, 1/2) << endl; //pow (number, exponent value)

        //cbrt(); cube root
        cout << "The cube-root of 8 is " << cbrt(8) << endl;
        cout << "The cube-root of 8 is " << pow (8, 1/3) << endl; //pow (number, exponent value)
    }
    
EXERCISE

SLIDE 5, Exercise

    #include <iostream>
    #include <math.h>
    #include <string>
    using namespace std;

    int main()
    {
        double num;

        cout << "Enter a number: ";
        cin >> num;
        while (cin.fail())
        {
            cin.clear();
            cin.ignore();
            cout << "\nInvalid input, enter a valid number." << endl;
            cin >> num;
        }
        cout << "\nSquare root of " << num << " is " << sqrt(num);
        cout << "\nCube root of " << num << " is " << cbrt(num) << endl;

    }
