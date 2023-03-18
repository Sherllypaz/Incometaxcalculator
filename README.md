# Incometaxcalculator
Tax_Rate = 0.20
StandardDeduction = 10000
DependentDeduction = 3000
 
grossIncome = float(input("enter the gross income: "))
numDependents = int(input("Enter the number of dependents: "))

taxableIncome = grossIncome-StandardDeduction-DependentDeduction*numDependents
incomeTax = taxableIncome * Tax_Rate

print("the income tax is $" + str(incomeTax))
