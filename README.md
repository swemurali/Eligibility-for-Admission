# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
## Step 1:
Declare variables for maths, physics, chemistry, and totalMarks.

## Step 2:
Use the Console.ReadLine() to get the inputs from the user.

## Step 3:
Calculate totalMarks as per the elegibility is mentioned.

## Step 4:
Check whether the student is eligible for admission using if else condition wth the given eligibility criteria.

## Step 5:
Use the Console.WriteLine() to display the eligibility status of the student.

## Program:
```
NAME : SUWETHA.M
REG NO :212221230112
```
```
using System;
class EligibilityforAdmission
{
    static void Main(string[] args)
    {
        int maths, physics, chemistry, totalMarks1 ,totalMarks2;
        string name;
        Console.Write("Enter the student name: ");
        name = Console.ReadLine();

        Console.Write("Enter the marks obtained in maths: ");
        maths = Convert.ToInt32(Console.ReadLine());

        Console.Write("Enter the marks obtained in physics: ");
        physics = Convert.ToInt32(Console.ReadLine());

        Console.Write("Enter the marks obtained in chemistry: ");
        chemistry = Convert.ToInt32(Console.ReadLine());

        totalMarks1 = maths + physics + chemistry;
        totalMarks2 = maths + physics;
        if (maths >= 65 && physics >= 55 && chemistry >= 50 && totalMarks1 >= 180 || totalMarks2 >= 140)
        {
            Console.WriteLine(name+" you are eligible for admission.");
        }
        else
        {
            Console.WriteLine(name+" you are not eligible for admission.");
        }
        Console.ReadLine();
    }
}
```


## Output:
![i 1](https://user-images.githubusercontent.com/94165336/226677956-625bed5d-fdfb-427d-ac31-785c59bc9a60.png)
![i 2](https://user-images.githubusercontent.com/94165336/226678004-c5b134c6-1b27-4599-8e8e-061c7eb8e057.png)

## Result:
Thus, C# program to find the eligibility for admission to an engineering course has been executed successfully.
