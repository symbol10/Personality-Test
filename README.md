# Personality-Test
print("Title of program: Personality test")
print()
print("Welcome to DHS! Please answer the following questions truthfully and we'll suggest a CCA for you!")
print("Please respond with a number 1 - 5, where 1 is strongly disagree and 5 is strongly agree.")
print()

kind1 = input("I enjoy helping others.")

outdoor1 = input("I'll go crazy if I do not go out of the house for the whole day.")

kind2 = input("I will help and support the people in need.")

daring1 = input("I am not afraid of anything.")

outdoor2 = input("I'm good with sports.")

daring2 = input("I am able to do anything as long as I have the will to do it)


kind_final = int(kind1) + int(kind2)
outdoor_final = int(outdoor1) + int(outdoor2)
daring_final = int(daring1)+ int(daring2)

print()

if kind_final > outdoor_final and kind_final > daring_final:
  print("You are a kind person who loves to help others :D")
elif outdoor_final > daring_final:
  print("You are an adventurous person who eagerly awaits any adventure!")
else:
  print("You are a daring person who can overcome anything!")

  
