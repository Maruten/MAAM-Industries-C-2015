# MAAM-Industries-C-2015
//The mission of MAAM Industries is to empower a bright new future for programming. 
//Using expert level coding skills, our company's desire to shape a new beginning for 
//the future of programming will be achieved. 

#include <iostream>

using namespace std;

void food(double, double, double, double, double);
void transportation(double, double, double, double);
void hospitality(double, double, double, double, double);//Function Prototypes
//Needs stubs and Drivers

int main()
{
  cout << fixed << showpoint << setprecision(2);
  double Food(foodvalue);
  double Transportation(transvalue);
  double Hospitality(hospitalvalue);
  cout << “The total cost of the trip was: “ << foodvalue + transvalue + hospitalvalue << endl;

  return 0;
}

//Display total cost and do not accept negatives

// This function ask the user for all of his or her transporting fees. 
// Then the transportation is called into int main with all the other functions.

void tranportation()
{
    // Delcare variables
    char car, plane;
    double departure;
    double ticketcost, rentalcost, taxicost;
    double miles, parkingfee;
    double totalcost;
    
    // Get user input
    cout << "Put in the time of departure: " << endl;
    cin >> departure;

    cout << "Put in the time of arrival back home: " << endl;

    cout << "Did you get on a plane? (y/n) " << endl;
    cin >> plane;

    if (plane = 'y')
    {
    cout << "What was the cost of the plane ticket? " >> endl;
    cin >> ticketcost;

    else if (plane = 'n')

    }
    cout << "Did you rent a car? (y/n) " << endl;
    cin >> car;

        if (car = 'n')
        {
        cout << "Put in the amount spent on the rental car: " << endl;
        cin >> rentalcost;

        cout << "How many miles were driven from the rental car? " << endl;
        cin >> miles;

        cout << "How many days were you charged for parking fees? " << endl;
        cin >> parkingfee;

        else if (car = 'n')
        }
        cout << "Did you take a taxi? (y/n)"
            if (taxi = 'y')
            {
                cout << "What was the total cost of taxi fees? " << endl;
                cin >> taxi:
            }
          totalcost = departure + ticketcost + rentalcost + taxicost + miles + parkingfee;
          
          transportation() = totalcost 
          
    return 0;
    }
    // End of program
    
void food(double bfast, double lonch, double dindin)
{
  int arrival, departure;
  cout << "Please enter the time of your arrival." << endl;
  
  // day 1: get breakfast if departure is before 7am 
  // lunch if departure is before 12 noon
  // dinner if departure is before 6pm
  
  // last day: breakfast if arrival is after 8am 
  // lunch if arrival is after 1pm
  // dinner is arrival is after 7pm 
  
  // ask for amounts of allowable meals??? 
  
}

//Things to ask for (checkbox):
Total days []
Time of departure, time of arrival back home []
(If) Roundtrip fare []
(If) Car Rentals []
(If) Private Vehicle Miles Driven - $0.27 per mile as constant []
(If) Parking Fees - $6.00 per day []
(If) Taxi Fees - $10.00 per day []
(If) Conference/Registration fees []
Hotel Expenses - $90.00 per day []
EACH MEAL:
Breakfast - $9.00 []
Lunch - $12.00 []
Dinner - $16.00 []
