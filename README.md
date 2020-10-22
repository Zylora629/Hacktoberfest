# Hacktoberfestprint("Title of program: Personality test")
print()
print("Welcome to my little quiz! Please answer the following questions truthfully and we'll analyse your personality for you!")
print("Please respond with a number 1 - 5, where 1 is strongly disagree and 5 is strongly agree.")
print()

tech1 = input("I am a calm person.")

outdoor1 = input("I play at least 1 musical instrument.")

music1 = input("I help people in need.")

tech2 = input("I am a good listening ear.")

outdoor2 = input("I'm amazing at cheering someone up.")

music2 = input("I do not get irritated easily.")


tech_final = int(tech1) + int(tech2)
outdoor_final = int(outdoor1) + int(outdoor2)
music_final = int(music1)+ int(music2)

print()

if tech_final > outdoor_final and tech_final > music_final:
 print("You have an interesting personality! Your peers must like you a lot! ")
elif outdoor_final > music_final:
 print("You have an interesting personality! Your peers must enjoy your company!")
else:
 print("You have an interesting personality! Your peers must love having you around!")
