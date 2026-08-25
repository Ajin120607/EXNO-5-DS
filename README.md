# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

DEVELOPED BY : AJIN A

REGISTER NO : 212224230011

# Coding and Output:
 ````
import pandas as pd 
import numpy as np 
import seaborn as sns
import matplotlib.pyplot as plt
marks=[13,45,63,78] 
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student) 
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()


student=['A','B','C','D'] 
attendence=[90,85,73,88]
plt.plot(attendence,student) 
plt.xlabel('Attendence') 
plt.ylabel('Student name')
plt.show()

````

<img width="576" height="432" alt="download" src="https://github.com/user-attachments/assets/6521ca28-9144-4d9c-b62b-896ac4ab33d5" />
<img width="556" height="432" alt="download" src="https://github.com/user-attachments/assets/cdf1e831-704f-4377-9a4e-e6eb03178c7a" />

````
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()

x=np.arange(0,15)
y=np.arange(0,15)
x
y
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('y axis')
plt.title('Scatter plot')
plt.show()

````


<img width="552" height="413" alt="download" src="https://github.com/user-attachments/assets/256635be-58c2-4dec-b276-f20e77a47690" />





<img width="563" height="453" alt="download" src="https://github.com/user-attachments/assets/57e5756a-d25f-418d-b7e7-8e1b8fd315dd" />



`````

act=['eat','sleep','work','play'] 
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%') 
plt.legend()
plt.show()

`````


<img width="452" height="415" alt="download" src="https://github.com/user-attachments/assets/d834337e-46af-496d-a8e3-f4fc50d76e04" />


````

feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%') 
plt.legend()
plt.show()

````

<img width="440" height="401" alt="download" src="https://github.com/user-attachments/assets/d7412cf1-6f57-406a-a7f0-16db50847f45" />



````
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]

plt.fill_between(x, y1, color='blue') 
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()


````

<img width="556" height="413" alt="download" src="https://github.com/user-attachments/assets/b4cd14f6-d824-4559-a655-1d482dfda2ba" />


````


height = [10, 24, 36, 40, 5] 
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green']
plt.bar (names, height, width=0.8, color=c1) 
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!') 
plt.show()



````

<img width="563" height="453" alt="download" src="https://github.com/user-attachments/assets/ef453d1b-9be2-4bd7-867c-1b0074bb2f67" />



````
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()

````


<img width="534" height="413" alt="download" src="https://github.com/user-attachments/assets/06c4b476-2a59-4da5-aacb-4e91c5f0b4fa" />

````

np.random.seed(0) 
data=np.random.normal(loc=0, scale=1, size=100)
data

````



<img width="712" height="442" alt="image" src="https://github.com/user-attachments/assets/d69706b5-085e-4838-89aa-216169581cf5" />


````

fig, ax= plt.subplots() 
ax.boxplot(data) 
ax.set_xlabel('Data')
ax.set_ylabel('Values') 
ax.set_title('Box Plot')


````

<img width="565" height="453" alt="download" src="https://github.com/user-attachments/assets/9133a5a9-2293-4771-a368-60b132b93d13" />





# Result:
 Thus, all the data visualization techniques of matplotlib has been implemented.
