#include <stdio.h>
#include <stdlib.h>

struct employee
{
  char name[100];
  int id;
  int experience;
  int salary;
};
int main()
{
  int i = 0;
  printf("Enter Employee details");
  struct employee s1[5];
  for (i = 0; i < 5; i++)
  {
    printf("\nEmployee %d", i + 1);
    printf("\nEnter the name of employee: ");
    scanf("%s", s1[i].name);
    printf("Enter the employee id: ");
    scanf("%d", &s1[i].id);
    printf("Enter experience year/years: ");
    scanf("%d", &s1[i].experience);
    printf("Enter salary: ");
    scanf("%d", &s1[i].salary);
  }

  printf("\nEmployee Details");
  for (int i = 0; i < 5; i++)
  {
    printf("\nEmployee %d \n", i + 1);
    printf("Name of employee: %s \n", s1[i].name);
    printf("Employee ID: %d \n", s1[i].id);
    printf("Year of Experience: %d \n", s1[i].experience);
    printf("Salary: %d \n", s1[i].salary);
  }

  return 0;
}
