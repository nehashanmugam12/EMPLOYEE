#include <stdio.h>
struct employee
{
    int num,age,salary;
    char name[25];
}emp[100];
 
int main()
{
    int i,n;
    printf("Enter the no of employees\n");
    scanf("%d",&n);
    printf("Enter employee info as phone number, name , age , salary\n");
    for(i=0;i<n;i++)
    {
        scanf("%d %s %d %d",&emp[i].num,emp[i].name,&emp[i].age,&emp[i].salary);
    }
    printf("\nEMPLOYEE NUMBER\tEMPLOYEE NAME\tEMPLOYEE AGE\tEMPLOYEE SALARY\n");
    for(i=0;i<n;i++)
    {
        printf("%d\t\t%s\t\t%d\t\t%d\n",emp[i].num,emp[i].name,emp[i].age,emp[i].salary);
    }
}
