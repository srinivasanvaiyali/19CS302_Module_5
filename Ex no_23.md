# EX 23 C program to store and display the name, id, age and salary of an employee using structure(using array of structure).
## DATE:
## AIM:
To write a C program to store and display the name, id, age and salary of an employee using structure(using array of structure).

## Algorithm
1. Start.
2. Define a variables.
3. Write program to to store and display the name, id, age and salary of an employee using structure(using array of structure).
4. Read the value using scanf.
5. Ask the user to make an input.
6. Print out the answer.
7. End.
  

## Program:
```
/*
C program to store and display the name, id, age and salary of an employee using structure(using array of structure).
Developed by: SRINIVASAN V
RegisterNumber:  212222043008
*/
```
```
#include<stdio.h> 
struct employee
{
int id,age,salary; 
char name[30];
}emp[100]; 
int main()
{
int i,n; 
scanf("%d",&n); 
for(i=0;i<n;i++)
{
scanf("%d %s %d %d",&emp[i].id,emp[i].name,&emp[i].age,&emp[i].salary);
}
printf("Employee Details\n"); 
for(i=0;i<n;i++)
printf("%d %s %d %d\n",emp[i].id,emp[i].name,emp[i].age,emp[i].salary);}
```

## Output:

<img width="1055" height="274" alt="438867502-e7e275ee-3254-455a-9d48-14b0e2a2adeb" src="https://github.com/user-attachments/assets/44b43787-0183-431e-a4f5-5b0274c20af1" />



## Result:
Thus the program was executed and the output was verified successfully.
