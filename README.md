# Python programming for data science
There are thousant of babies born every day in the world and sometime it's not easy to find a name for your baby.
for that reason i created this data analyze program with python.

from a chart of the names of the babies born from 1800 to 2020 in usa we collect this information:

class baby( id, name, year, gender, count)

now as someonee trying to find a name, i am going to select first my baby names gender.
for that i creater a funtion that assemble every same gender and give each gender an int number.
as in the chart we only have MALE and FEMALE, that mean that we can only have two number.
MALE=1 and FEMALE=0.

now that we chose the baby name's gender there are still alot of name to choose from.
So i created another function transforming every letter in the alphabet to number, then transform every name into a sycle of number.

that made the searching easy for us. because now ce can tell the programe the letter we want our baby's name tobegin with.

even after that we can still choose the lenght of the name we want and just like that you can choose your baby's name.


but since we transformed the letter to number, we not gonna give the baby a number composed by number. so for that i created another 
function that after the search transform the number back to strings (letter) and voila we have the baby's name.
