# circle
Calculate area, diameter and circumference of a circle

//  main.cpp



#include <iostream>
#include <cmath>
using namespace std;

// Write function to calculate the area of a circle

int calcArea( int radius ) {
    int area = 0;
    const float PI = 3.1416;
    area=pow(radius,2)*PI;
    return area;
    
}

// Write function to calculate the diameter of a circle

int calcDiameter( int radius ) {
    int diameter = 0;
    diameter = 2 * radius;
    return diameter;
}

// Write function to calculate the circumerence of a circle

int calcCircumference( int radius ) {
    int circumference = 0;
    const float PI = 3.1416;
    circumference = 2 * radius * PI;
    return circumference;
}

int main() {
    
    // calculate area of a circle based on specified parameters
    
    cout << "Area of the circle is " << calcArea(10) << endl;
    cout << "Area of the circle is " << calcArea(12.5) << endl;
    cout << "Area of the circle is " << calcArea(1.03) << endl;
    
     // calculate diameter of a circle based on specified parameters
    
    cout << "Diameter of the circle is " << calcDiameter(10) << endl;
    cout << "Diameter of the circle is " << calcDiameter(12.5) << endl;
    cout << "Diameter of the circle is " << calcDiameter(1.03) << endl;
    
     // calculate circumference of a circle based on specified parameters
    
    cout << "Circumference of the circle is " << calcDiameter(10) << endl;
    cout << "Circumference of the circle is " << calcDiameter(12.5) << endl;
    cout << "Circumference of the circle is " << calcDiameter(1.03) << endl;
    
    return 0;

    
}



