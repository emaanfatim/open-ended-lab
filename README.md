#include<iostream>
#include<ctime>
using namespace std;
int main()
{
	int books, issuedate, fine, days;
	int booksreturndate = 0;
	cout << "How many books do you want to issue";
	cin >> books;
	cout << "Enter currentdate";
	cin >> issuedate;
	cout << "Enter issuedate";
	cin >> issuedate;
	days = booksreturndate - issuedate;
	if (days>=5)
	{
		cout << "You are fined for late book return";
		fine = days * 1;
	}
	return 0;
	
}
