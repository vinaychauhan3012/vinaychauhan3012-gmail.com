#include<iostream> 
using namespace std;
#include<stdbool.h>
class Requirement
{
 	public: bool pen ;
	public: bool paper ;
	public: bool question_paper ;
	public: bool all_three ;
};
int main()
{
	int n=3;
	Requirement  R[n];
	R[0].pen=true;		
	R[0].paper = false;
	R[0].question_paper = false;
	R[0].all_three= false;
	R[1].pen=false;		
	R[1].paper = true;
	R[1].question_paper = false;
	R[1].all_three = false;
	R[2].pen=false;		
	R[2].paper = false;
	R[2].question_paper = true;
	R[2].all_three = false	;
	while(R[0].all_three==false||R[1].all_three==false||R[2].all_three==false)
	{
		int ch1,ch2;
		cout<<"\nResources:\n1.pen\n2.paper\n3.question paper\n Enter the two things which is to be placed on the shared table: ";
		cin>>ch1>>ch2;
		if(ch1==1 && ch2==2 && R[2].all_three==false)
		{
			R[2].all_three=true ;
			cout<<"Third Student has completed the task\n";
		}
		if(ch1==2 && ch2==3 && R[0].all_three==false)
		{
			R[0].all_three=true;
			cout<<"First Student has completed the task\n";
		}
		if(ch1==1 && ch2==3 && R[1].all_three==false)
		{
			R[1].all_three=true;
			cout<<"Second Student has completed the task\n";
		}
	}
	cout<<"All the students now have completed their respective tasks succesfully\n";
	return 0;
}
