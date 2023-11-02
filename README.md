#include<iostream>
using namespace std;
int main()
{int books, days,rollnumber;
	int fine = 1;
	int returndate ;
	int issuedate ;
	cout << "How many books do you want to issue:";
	cin >> books;
	cout << "Tell me your roll number:";
	cin >> rollnumber;
	cout << "Enter issue date:";
	cin >> issuedate;
	cout << "Enter return date:";
	cin >> returndate;
	days = returndate - issuedate;
	if (days >= 6)
		// The fine start calculating from 6th day till the user returned the book.
	{fine = days - 4;
		cout << "The total fine for late return is:" << fine << " " << "dollars";
	}
	  else
	  {
		  cout << "There is no fine";
	  }
	return 0;
}
	

