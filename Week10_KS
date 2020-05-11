
#!/usr/bin/env python3

#load the re module
import re
#create a file object from the covid data file
dataFile = open("covidData_3.30.20.txt","r")
#match all the louisiana parishes and make a list
with open("covidData_3.30.20.txt") as f:
        all_parishes = re.findall(r'(\w\w+),Louisiana',f.read())
# matches = re.findall(r"(\d\w)^Louisiana(\$)","dataFile")* this didnt work
# close the covid data file object
dataFile.close()
#print out parishes results
print(all_parishes)
#create a dictionary with all of the parishes
Parishesdict = {}
Parishesdict["LA"] = ["Jefferson", "Orleans","Caddo","St Charles","Tammany","Terrebon$
dataFile.open("covidData_3.30.20.txt")
fname=input("covidData_3.30.20.txt")
fname = input("Orleans")
#count the occurances of Orleans in the file (change to include other parishes)
with open("covidData_3.30.20.txt") as f:
        for line in f:
        words=line.split()
        for i in words:
                if(i==word):
                k=k+1
print("Occurances of the word:")
print(k)
#for i in Parishesdict:
#       print i
dataFile.close()
# use a regex search to find the 1st instance of a LA parish recorded a death
dataFile.open("covidData_3.30.20.txt","r")
re.search(r"deaths >= 0",f.read())
if re.search(r"deaths >= 0",f.read())
        print("This parish had the earliest entry:")
else:
        print("Pattern not found!")
dataFile.close()
# Now we need to create a new file that only has records from Louisiana.
# Extract the lines that pertain to Louisiana and write them to a new file.
LAonlyPar=open(r"covidData_3.30.20.txt","r+")
with open("covidData_3.30.20.txt")
        for line n dataFile.writelines(all_parishes)
LAonlyPar.close()
# Lastly, let's imagine that we want to do further downstream analyses with
# the Louisiana data, but our downstream analyses require some formatting chanages.
# Read in the lines from your newly created file with only Louisiana records, reforma$
# and create a separate file to hold the newly formatted information. Specifically, tthe
# dates in the file should be reformatted from looking like this (2020-MM-DD) to looking
# like this (MM.DD.2020). Also, the fips codes (in the 4th column) should be removed, and
# Louisiana should be abbreviated as LA. So, this file should end up with entries that look
# like this: 03.25.2020,Morehouse,LA,1,0# Now we need to create a new file that only has records from Louisiana an$
dataFile.open("LAonlyPar.txt","w")
        with open("LAonlyPar.txt")
        for line in dataFile.writelines(all_parishes)
        re.sub(w"(\w\w)(Louisiana)(\w\w)",r"\1|\2\ ", LAonlyPar.txt")
dataFile.close()

