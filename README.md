# Soumyadip005-Coursera-Python-for-Specialization-3.1

hrs = input("Enter Hours: ")

rate = input("Enter rate per hour: ")

h = float(hrs)

r = float(rate)

if h > 40 :
	regp = float(hrs) * float(rate)
	otp = (h-40.0) * (r * 0.5)
	pay = regp + otp

else:
	pay = float(hrs)*float(rate)

print (pay)
