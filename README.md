# ex_3_employee_first_steps_in_OOP_exercise

Create class Employee. Upon initialization, it should receive id (number), first_name (string), last_name (string) and salary (number). Create 3 additional instance methods:
-	get_full_name() - returns "{first_name} {last_name}"
-	get_annual_salary() - returns the total salary for 12 months
-	raise_salary(amount) - increases the salary by the given amount and returns the new salary

Test Code
employee = Employee(744423129, "John", "Smith", 1000)
print(employee.get_full_name())
print(employee.raise_salary(500))
print(employee.get_annual_salary())

Output
John Smith
1500
18000
