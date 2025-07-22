print("-----Welcome to BMI Calculator-----")
Name=input("Enter the name of the Person :-")
Age=int(input("Enter the age of the Person :-"))
Height=float(input("Enter your Height(in meters) :-"))
Weight=float(input("Enter your Weight(in kgs) :-"))
BMI= Weight/(Height**2)
print("Your Body Mass Index is:",round(BMI,2))

if BMI<=18.5:
	print("You are UNDERWEIGHT")
	print("focus on gradually increasing calorie intake with nutrient-rich foods and engaging in strength training to build muscle mass")
elif BMI<=24.9:
	print("You are HEALTHY")
	print("Doing Great, Keep Going")
elif BMI<=29.9:
	print("You are OVER WEIGHT")
	print("focus on sustainable lifestyle changes involving diet and exercise")
else:
	print("You jave OBESITY")
	print("focus on a comprehensive approach involving a balanced, calorie-controlled diet, regular physical activity, and lifestyle adjustments, with options for medical interventions if needed")
 
