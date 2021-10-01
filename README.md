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
    while (true) {
        int numberofSides;
        cout << "\nShape DeterminatorInator\n";
        cout << "\nHow many sides does the shape have?\n\n";
        cin >> numberofSides;
        if (numberofSides>=3&&numberofSides<4)
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
//PAGE 16
#include <iostream>
using namespace std;
int main()
{	
	while (1)
	{
		cout << "Grading System Inator\n\n";
		double grade;
		cout << "Input the grade of the student\n\n";
		cin >> grade;
		if (grade < 40)
		{
			cout << "\nGive the student a F\n\n";
		}
		else if (grade >= 40 && grade <= 49)
		{
			cout << "\nGive the student a D\n\n";
		}
		else if (grade >= 50 && grade <= 59)
		{
			cout << "\nGive the student a C\n\n";
		}
		else if (grade >= 60 && grade <= 69)
		{
			cout << "\nGive the student a B\n\n";
		}
		else if (grade >= 70)
		{
			cout << "\nGive the student an A\n\n";
		}
	}
}
//PAGE 17

#include <iostream>
#include <string>
using namespace std;
int main()
{
	bool musicalFriend;
	cout << "Hey friend! if you play an instrument press 1 if not press 0\n\n";
	cin >> musicalFriend;
	if (musicalFriend)
	{
		string friendPlays = "guitar";
		string whatdoesfriendplay;
		cout << "\nWhat instrument do you play\n\n";
		cin >> whatdoesfriendplay;
		if (friendPlays==whatdoesfriendplay)
		{
			cout << "\nNoice you're in we have a gig tonight\n\n";
		}
		else
		{
			cout << "\nYou ain't my friend no more get out of here!\n\n";
		}
	}
	else
	{
		cout << "\nWhy are you even here?\n\n";
	}


}

//PAGE 19

#include <iostream>
#include <string>
using namespace std;
int main()
{
	cout << "What to do when waiting for a friend\n\n";
	int x;
	cout << "Type how many minutes longer will your friend take to arive\n\n";
	cin >> x;
	if (x>=15)
	{
		cout << "\nYou're friend will arive 15 or more minutes later what do you want to do?\n\n";
		double c;
		cout << "How much money do you have?\n\n";
		cin >> c;
		if (c>=5)
		{
			cout << "\nGo buy a coffee while waiting for your friend who is always late and you shouldnt tolerate that\n\n";
		}
		else
		{
			cout << "\nGo for a walk and contemplate why you're still friends with someone who doesn't value your time\n\n";
		}
	}
	else
	{
		cout << "\nThis guy is a good friend he'll be here in less than 15 minutes just sit in the food court and wait but,\nyou will be hungry because you will smell all the food\n\n";
	}
}

//PAGE 20

#include <iostream>
using namespace std;
int main()
{	
	cout << "MagnitudeInator for earthquaktes\n\n";
	cout << "is there an earthquake? Type Yes or No only\n\n";
	string x;
	cin >> x;
	if (x == "yes" || x == "Yes")
	{		
			cout << "\nWhat is the magnitude of the earthquake?\n\n";
			double magnitude;
			cin >> magnitude;
			if (magnitude < 2)
			{
				cout << "\nThis is only a micro earthquake stay calm\n\n";
			}
			else if (magnitude >= 2 && magnitude <= 3)
			{
				cout << "\nThis earthquake is not that bad its very minor be calm\n\n";
			}
			else if (magnitude >= 3 && magnitude <= 4)
			{
				cout << "\nThis earthquake is minor but stay indoors and avoid windows just incase\n\n";
			}
			else if (magnitude >= 4 && magnitude <= 5)
			{
				cout << "\nThis is a light earthquake find shelter\n\n";
			}
			else if (magnitude >= 5 && magnitude <= 6)
			{
				cout << "\nThis is a Moderate earthquake!! if you are outdoors find open ground and stay low avoid buildings\n\n";
			}
			else if (magnitude >= 6 && magnitude <= 7)
			{
				cout << "\nThis Earthquake is a Strong earthquake find something solid like a table and go under it, if you are outdoors find open ground\n\n";
			}
			else if (magnitude >= 7 && magnitude <= 8)
			{
				cout << "\nThis is a Major Earthquake!! say your prayers\n\n";
			}
			else if (magnitude >= 8 && magnitude <= 10)
			{
				cout << "\nThis is a Great earthquake there's not much to do anymore but pray\n\n";
			}
			else if (magnitude > 10)
			{
				cout << "\nHave you watched the movie 2012? yeah this is it, you gonna die, there is no hope, Goodbye :)\n This is a Meteoric Earthquake\n\n";
			}		
	}
	else
	{
		cout << "\nThere is no Earthquake chill\n\n";
	}
}


  
