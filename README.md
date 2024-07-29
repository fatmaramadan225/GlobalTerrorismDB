# GlobalTerrorismDB
step 1 _data cleaning
I meet problem in reading data normally with pandas so I used
chardet library to know encoding of data
Data encoding is: Windows-1252
handling problems in data
1- a lot of missing values
Drop columns with too large number of missing values
2- There are 0 in month and day columns
Replace 0 with mode value
3- Unnecessary columns
Delete unnecessary columns
4- Data types
Change datatypes
5- Fromat
Change text columns in consistent fromat (make all text
lower)
6- Rename columns
7-check If data contains duplicates
step 2 : Data analysis and visualization
Libraries:
numpy
Pandas
seaborn
matplotlib
Insights
1- Most attacks happened in 2014
2- Most attacks happened in middle east & north Africa(47978)
attack ,south Asia (43191) attack
3- Top 10 targets
Civilians
Patrol
Soldiers
Vehicle
Checkpoint
Officers
Unit
village
military unit
bus
4- Top 10 attack group
taliban
islamic state of iraq and the levant (isil)
shining path (sl)
new people's army (npa)
al-shabaab
farabundo marti national liberation front (fmln)
irish republican army (ira)
revolutionary armed forces of colombia (farc)
kurdistan workers' party (pkk)
boko haram
5- Most popular weapon type explosives ,firearms
6- Most affected countries
Iraq
Pakistan
India
Afghanistan
Colombia
Philippines
Peru
united kingdom
Turkey
el salvador
