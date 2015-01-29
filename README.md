# MAAM-Industries-C-2015
//The mission of MAAM Industries is to empower a bright new future for programming. 
//Using expert level coding skills, our company's desire to shape a new beginning for 
//the future of programming will be achieved. 

#include <iostream>

using namespace std;

Void food(double, double, double, double, double);
Void transportation(double, double, double, double):
Void hospitality(double, double, double, double, double);//Function Prototypes
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

void food(double bfast, double lonch, double din2)
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
