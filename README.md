# L5-Codes


Biography 

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        string name;
        string age; 
        string address;

        cout << "Name: " << endl;
        cin >> name;
        cout << "Age: " << endl;
        cin >> age;
        cout << "Address:" << address << endl;
        cin >> address;

        cout << "Name: " << name << endl;
        cout << "Age: " << age << endl;
        cout << "Address: " << address << endl;
    }
  
  
  Temperature
  
    #include <iostream>
    using namespace std;

    int main()
    {
        double farenheit;
        double celcius;

        cout << "Please enter the temperature in Farenheit: " << endl;
        cin >> farenheit;
        celcius = (farenheit - 32) * 0.5556;
        cout << "= " << celcius << " Celcius" << endl;
    }
  
  
  Circles
  
    #include <iostream>
    using namespace std;

    int main()
    {
        double a; 
        double c;
        double r;

        cout << "Radius: " << endl;
        cin >> r;

        a = 3.14 * r * r;
        c = 2 * 3.14 * r;

        cout << "Area of the circle: " << a << endl;
        cout << "Circumference of the circle: " << c << endl;
    }

  
  Rectangle Triangle Square
  
    #include <iostream>
    using namespace std;

    int main()
    {
        double rectangle;
        double triangle;
        double square;
        double length;
        double width;

        cout << "Area of Rectangle, Triangle and Square " << endl;
        cout << "Length: " ;
        cin >> length;
        cout << "Width: " ;
        cin >> width;

        rectangle = length * width;
        triangle = (length * width) * 0.5;
        square = length * length;

        cout << "The area of the rectangle is: " << rectangle << endl;
        cout << "The area of the triangle is: " << triangle << endl;
        cout << "The area of the square is: " << square << endl;
    }
