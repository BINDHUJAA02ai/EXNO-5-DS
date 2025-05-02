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

# Coding and Output:
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.plot(x_values,y_values)
plt.show()
```
![377325214-641028c2-48ad-404e-91de-8eb0f40961ae](https://github.com/user-attachments/assets/318ad017-203f-4dec-8fb9-573a53616d57)
```
import matplotlib.pyplot as plt
x=[1,2,3]
y=[2,4,1]
plt.plot(x,y)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My first graph!')
plt.show()
```
![377325361-0fa3257c-5d5c-498d-9ec8-614e710fb82c](https://github.com/user-attachments/assets/46aa3a99-c5db-47d6-b2bd-3f68b0572ca9)
```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")
x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2,label="line 2")
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Two lines on same graph!')
plt.legend()
plt.show()
```
![377325495-51c39c65-17eb-4a28-8b2d-4d4cda9d780f](https://github.com/user-attachments/assets/1eaed812-cefb-4a12-a019-838746b17186)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]
plt.plot(x,y,color='green',linestyle='dashed',linewidth=3,marker='o',markerfacecolor='blue',markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Some cool customizations!')

plt.show()
```
![377325639-77189c88-eddd-4352-982b-d0efaba01fcf](https://github.com/user-attachments/assets/6c4cc175-858c-483e-ab48-e87c57dc9829)
```
yield_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(yield_apples)
```
![377325794-04803967-fe15-46a3-a5c4-40a9dcf58596](https://github.com/user-attachments/assets/8fc6da53-fcf0-4f8c-aeef-ccdfbe6b40d1)
```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
```
![377325982-0104529f-1073-4309-a09d-9bcb84dd4346](https://github.com/user-attachments/assets/250f6b6a-0c32-4e2f-8c5a-a88232d0e930)
```
years=range(2000,2012)
apples= [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![325089418-7f7c1cdb-b5e3-4fa0-bfaa-a758f3468e1e](https://github.com/user-attachments/assets/8d5eeae3-6d68-456c-9b69-4b1398447b76)

```
plt.plot(years,apples)
plt.plot(years,oranges)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![325089590-bffac794-5d8e-4696-ba5a-fdf995b5d7b6](https://github.com/user-attachments/assets/a7af4230-9abb-4848-a89b-3f5c016c0a24)
```
years=[2010,2011,2012,2013,2014,2015]
yeild_apples=[0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years,yeild_apples)
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)');
```
![325089763-4da08ae4-bbce-4a48-8b3e-2205eecf1e2d](https://github.com/user-attachments/assets/710c28bd-da54-423d-9a68-10597a3c9549)
```
years=range(2000,2012)
oranges=[0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896,]
plt.figure(figsize=(12,6))
plt.plot(years,oranges,marker='o')
plt.title("Yeild of Oranges (tons per hectare)");
```
![325089922-bbe836b1-fe5c-4962-9b5b-6d695aa8cc66](https://github.com/user-attachments/assets/1f38f2be-9093-4761-9444-56d7aa65e80e)
```
plt.plot(years,apples,marker='o')
plt.plot(years,oranges,marker='x')
plt.xlabel('Year')
plt.ylabel('Yeild(tons per hectare)')
plt.title("Crop Yeilds in Kanto")
plt.legend(['Apples','Oranges']);
```
![325090075-dedd396a-e83b-4b91-8d1a-5fdcd78bd115](https://github.com/user-attachments/assets/6dfa54d3-f4e4-451f-82d5-0ab20f83f1ad)
```
import matplotlib.pyplot as plt
x_values=[0,1,2,3,4,5]
y_values=[0,1,4,9,16,25]
plt.scatter(x_values,y_values,s=30,color="blue")
plt.show()
```
![325090217-493ffb54-af9e-41e4-ac31-fb0b49ff7811](https://github.com/user-attachments/assets/74dfe2c6-fd10-4896-acf7-dca375f2b9fc)
```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
```
y
```
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')
```
![325090676-8acee8db-9dd0-4ae0-91d4-42876ae11b9d](https://github.com/user-attachments/assets/cf47317c-afd6-4b65-807e-ae7bb6a3a533)

```
y=x*x
y
```
array([ 0, 1, 4, 9, 16, 25, 36, 49, 64, 81])
```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
```
![325091038-29adeffc-0967-434b-80e4-d78e9114a2cc](https://github.com/user-attachments/assets/1000d1e3-58a6-43eb-8f7e-858247daaa4f)
```
np.pi
```
3.141592653589793
```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![325091355-7c877f63-07bc-4b43-8c1f-630b615a8ba8](https://github.com/user-attachments/assets/1e1d4ad5-21bb-4ccf-bcdf-3c9ade370d61)
```
import matplotlib.pyplot as plt
import numpy as np
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.fill_between(x,y1,color="blue")
plt.fill_between(x,y2,color="green")
plt.plot(x,y1,color="red")
plt.plot(x,y2,color="black")
plt.legend(['y1','y2'])
plt.show()
```
![325091527-a70aa17c-2503-429f-a59f-6defc86c99b3](https://github.com/user-attachments/assets/3f53b4e4-1bb5-4ce5-ac4f-22692f0f8ee6)
```
import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names,height,width=0.8,color=c1)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('My bar chart!')
plt.show()
```
![325091635-8b3b1d07-f746-42cd-818e-cf9ec41b997c](https://github.com/user-attachments/assets/1cde9829-db3b-4266-bd7c-30fe296d30cd)
```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,11]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![325091894-bfb1c2f6-a934-456c-8996-0443342dabeb](https://github.com/user-attachments/assets/88bb2d94-95b4-4b4d-b97c-6f5989fceee7)
```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No.of people')
plt.title('My histogram')
plt.show()
```
![325092069-4553d48d-5135-498b-8298-35bde4c5bd1a](https://github.com/user-attachments/assets/89dcb850-784a-4e4a-a90f-93da274ccf53)

![325092069-4553d48d-5135-498b-8298-35bde4c5bd1a](https://github.com/user-attachments/assets/b0c2abb2-0fdb-4558-a099-9e639af4229e)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![325092285-5ee92819-726b-4314-8755-6fa9c4a27b4d](https://github.com/user-attachments/assets/c1d2a0ad-4e71-4951-9fd7-27f6f01de520)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box plot'
```
![325092388-fa0d26b7-f04b-45a1-8879-b4165a717fb0](https://github.com/user-attachments/assets/5954ca72-26f6-4ae8-b17d-81f702c0bb9c)
```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)
plt.pie(sizes,explode=explode,labels=labels,colors=colors,
autopct='%1.1f%%',shadow=True)
plt.axis('equal')
plt.show()
![325092569-d561d300-95bc-4ce4-bde3-7b983c9c1576](https://github.com/user-attachments/assets/e80fe9d4-c793-4a79-b169-d1e677357fac)
```
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,
        startangle=90,shadow=True,explode=(0,0,0.1,0),
        radius=1.2,autopct='%1.1f%%')
plt.legend()
```
![325092667-276099eb-e297-47a1-a8d9-aa39183c8464](https://github.com/user-attachments/assets/a8967cbc-f2b5-4642-bd47-6e3402db3690)







# Result:
To Perform Data Visualization using matplot python library for the given datas is successful.
