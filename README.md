
unit=input("Enter Unit")
if unit=="km":
 km=int(input("Enter km"))
 miles=km* .62
 print(miles) 
elif unit=="miles":
  miles=int(input("Enter miles"))
  km=miles*1.6
  print(km)
elif unit=="lbs":
  lbs=int(input("Enter lbs"))
  kg=lbs*45
  print(kg)
elif unit=="kg":
  kg=int(input("Enter kg"))
  lbs=kg*2.2
  print(lbs)
elif unit=="Gallon":
  Gallon=int(input("Enter Gallon"))
  Quart=Gallon*4
  print(Quart)
else:
  quart=int(input("Enter quart"))
  Gallon=quart*.25
  print(Gallon)
