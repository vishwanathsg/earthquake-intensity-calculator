# earthquake-intensity-calculator
This code tells the intensity of an earthquake when magnitude is entered

#Earthquake Impact: Input some numbers, do some simple arithmetic, output results

Mag=float(input("Enter magnitude (ranges from 1 to 10): "))
#Taking magnitude of Richter scale from user

I=10 ** Mag
#Simplified formula for calculating intensity of an earthquake

print("The intensity experienced during an earthquake of provided magnitude value is:", I )
print("times more than the base intensity")
