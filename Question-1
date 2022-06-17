#include <stdio.h>
 
int main()
{
	float Basic, HRA, DA, Gross_Salary;
  	
	printf("\n Please Enter the Basic Salary of an Employee  :  ");
  	scanf("%f", &Basic);
  
  	if (Basic <= 10000)
  	{
  		HRA = (Basic * 8) / 100; // or HRA = Basic * (8 / 100)
		DA = (Basic * 10) / 100; // Or Da= Basic * 0.1    	
  	} 
  	else if (Basic <= 20000)
  	{
  		HRA = (Basic * 16) / 100;
	  	DA = (Basic * 20) / 100;  	
  	}
  	else
  	{
	   	HRA = (Basic * 24) / 100; 
	   	DA = (Basic * 30) / 100;
	}
	Gross_Salary = Basic + HRA + DA;
	printf("\n Gross Salary of this Employee  =  %.2f", Gross_Salary); 
	
  	return 0;
}
