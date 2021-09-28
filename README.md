# Lecture-6-Exercise
Coding for Ms. Zainab
// Page 23 exercise 
#include <iostream>
using namespace std;
int main()
{
    int age;
    cout << "Age Checker for eligibility to vote \n";
    cout << "\n" << "Please state your age\n";
    cout << "\nWhat is your age? \n\n";
    cin >> age;
    if (age >= 18)
    {
        cout << "\nYou are eligible to vote\n";
    }
    else
    {
        cout << "\nYou are not allowed to vote since you are under 18\n";
    }

return 0;
    
}
// Page 24 exercise
  #include <iostream>
using namespace std;
int main()
{
    int number;
    cout << "Odd or Even Number Checker\n";
    cout << "\n" << "Please give a number of your choice\n\n";
    cin >> number;
    if (number%2==0)
    {
        cout << "\n" << number << " Is an Even Number\n";
    }
    else
    {
        cout << "\n" << number << " Is not an Even Number\n";
    }

    return 0;
    
}
// Page 25 Exercise
  #include <iostream>
using namespace std;
int main()
{
    int number;
    cout << "Sign of a number Checker\n";
    cout << "\n" << "Please give a number of your choice\n\n";
    cin >> number;
    if(number>=1)
    {
        cout << "\n" << number << " Is Positive\n";
    }
    else if (number<=-1)
    {
        cout << "\n" << number << " Is Negative\n";
    }
    else    
    {
        cout << "\n" << number << " Is Zero\n";
    }

    return 0;
    
}
//Page 26 exercise
#include <iostream>
using namespace std;
int main()
{
    int purchasePrice;
    int salePrice;
    cout << "Profit or Loss Calculatort \n\n";
    cout << "Please Input Purchase Price\n\n";
    cin >> purchasePrice;
    cout << "\nPlease Input Sale Price\n\n";
    cin >> salePrice;
    int moneyLost = (purchasePrice - salePrice);
    int moneyProfit = (salePrice - purchasePrice);
    if (purchasePrice>salePrice)
    {
        cout << "\nYou Lost " << moneyLost << "\n";
    }
    else if (purchasePrice<salePrice)
    {
        cout << "\nYou gained " << moneyProfit << "\n";
    }
    else
    {
        cout << "\nNo loss or profit, you earned your money back\n";
    }

    return 0;

}
// Page 27 exercise
#include <iostream>
using namespace std;
int main() {
    while (1) {
        int numberofSides;
        cout << "\nShape DeterminatorInator\n";
        cout << "\nHow many sides does the shape have?\n\n";
        cin >> numberofSides;
        if (numberofSides == 3)
        {
            cout << "\n" << "The shape is a Triangle\n";
        }
        else if (numberofSides == 4)
        {
            cout << "\n" << "The shape is a Quadrilateral\n";
        }
        else if (numberofSides == 5)
        {
            cout << "\n" << "The shape is a Pentagon\n";
        }
        else if (numberofSides == 6)
        {
            cout << "\n" << "The shape is a Hexagon\n";
        }
        else if (numberofSides == 7)
        {
            cout << "\n" << "The shape is a Heptagon\n";
        }
        else if (numberofSides == 8)
        {
            cout << "\n" << "The shape is a Octagon\n";
        }
        else if (numberofSides == 9)
        {
            cout << "\n" << "The shape is a Nonagon\n";
        }
        else if (numberofSides == 10)
        {
            cout << "\n" << "The shape is a Decagon\n";
        }
        else if (numberofSides > 10)
        {
            cout << "\nthis program can only determine shapes that have up to 10 sides, please input number of sides again\n";
        }
        else if (numberofSides < 3)
        {
            cout << "\nA Shape can't have less than 3 sides, Please run the program again\n";
            bool prgram;
            cout << "\nType 1 if you want to terminate the program and press 0 to try again\n\n";
            cin >> prgram;           
            if (prgram==true)
            {                            
                break;
            }
            
        }
    }
}

  
