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
x1=[1,2,3,4,5,6,7,8,9,10]
y1=[2,4,5,7,6,8,9,11,12,12]
plt.scatter(x1,y1,label='stars',color='green',marker='*',s=30)
plt.xlabel('x-axis')
plt.ylabel('y-axis')
plt.title('Scatter Plot')
plt.legend()
plt.show()
```
![441179889-a95c850a-9a43-4d4f-beb1-355d387f178d](https://github.com/user-attachments/assets/354ae648-877d-4b24-9088-c085a7135a49)

```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd
x=np.arange(0,10)
y=np.arange(11,21)
x
```
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9
```
y
```
![378767321-95e2f5f7-7125-4fd2-8ded-55dcea942673](https://github.com/user-attachments/assets/2bf87a2e-7a14-4d52-8366-2e235eea06c0)


```
plt.scatter(x,y,c='r')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graphs in 2D')
plt.savefig('Test.png')
```

![378767493-9ff66837-2f4d-4f96-8e45-ebaab5213302](https://github.com/user-attachments/assets/0370e832-9e1a-4741-af93-85533b739ac1)


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
![378767736-e9c12efc-f038-4e53-a155-3b7fc51a4764](https://github.com/user-attachments/assets/e5ecbe42-0206-48c6-b36f-d745a52d155a)

```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```
![378767847-806d0ac3-9926-4f8c-b482-f0e97558783d](https://github.com/user-attachments/assets/1e577b2d-2c0f-4d39-90bb-89b403961e5b)
```
np.pi
```
![378768009-7360eaa6-64c1-49a9-bf0c-73956c3453d7](https://github.com/user-attachments/assets/24bafbfd-2ca9-408e-ac49-ae58f2e03f30)

```
x=np.arange(0,4*np.pi,0.1)
y=np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```
![378768142-4d97f6e3-9b45-49d1-8b10-e79b4ad93b4e](https://github.com/user-attachments/assets/0ddc7f9d-d433-43c5-9a2f-026fb3572379)

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
![378768272-2971cf24-daa3-4e86-9eb1-053e7fda2ff6](https://github.com/user-attachments/assets/a85116d3-e441-4918-972d-28fe57d21274)

```
x=[1,2,3,4,5]
y1=[10,12,14,16,18]
y2=[5,7,9,11,13]
y3=[2,4,6,8,10]
plt.stackplot(x,y1,y2,y3,labels=['Line1','Line2','Line3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.show()

```
![378768391-48ae1fcc-d6bf-4b5a-8229-5fc4ea0894de](https://github.com/user-attachments/assets/b303105a-d733-490d-95e0-dc3a13ece1f3)

```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x = np.array([1,2,3,4,5,6,7,8,9,10])
y = np.array([2,4,5,6,7,8,8,10,11,12])
spl=make_interp_spline(x,y)
x_smooth=np.linspace(x.min(),x.max(),100)
y_smooth=spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()
```
![378768488-c8ff9b9d-1557-4b6e-bc30-a9e59593ae57](https://github.com/user-attachments/assets/1d659cd5-643e-4675-b4bd-f45c2224d676)

```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=['A','B','C','D','E']
plt.bar(names,values,color='green')
plt.show()
```
![378768706-1ed34b0f-18cb-45fe-b185-ecc7af85b3f2](https://github.com/user-attachments/assets/aba83960-0784-4bde-8e10-f8913a937dcf)



```
import matplotlib.pyplot as plt
values=[5,6,3,7,2]
names=['A','B','C','D','E']
plt.barh(names,values,color='yellowgreen')
plt.show()
```
![378768829-90ce15de-fa5a-430f-8b1c-f4f8e3f2b24f](https://github.com/user-attachments/assets/5ec099e4-fb16-406c-bf33-52e90151d6e5)

```

import matplotlib.pyplot as plt
height=[10,24,36,40,5]
names=['one','two','three','four','five']
c1=['red','green']
c2=['b','g']
plt.bar(names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.show()
```
![441181029-8f1e82c6-7f01-411a-98a9-ef5fa086d9d9](https://github.com/user-attachments/assets/ab1e5f38-292e-4b4e-85fc-02650de07b3b)

```
x=[2,8,10]
y=[11,16,9]
x2=[3,9,11]
y2=[6,15,7]
plt.bar(x,y,color='r')
plt.bar(x2,y2,color='g')
plt.title('Bar graph')
plt.ylabel('Y axis')
plt.xlabel('X axis')
plt.show()
```
![378769079-cb5855a2-a611-4cd3-b7e9-26b856920e92](https://github.com/user-attachments/assets/f2f3b659-60fb-4863-8a97-fd462a1ecb23)

```
import matplotlib.pyplot as plt
ages=[2,5,70,40,30,45,50,45,43,40,44,60,7,13,57,18,90,77,32,21,20,40]
range=(0,100)
bins=10
plt.hist(ages,bins,range,color='green',histtype='bar',rwidth=0.8)
plt.xlabel('age')
plt.ylabel('No. of people')
plt.show()
```
![441181223-86073fcd-eb4a-4dc7-bb13-c40cc36ebe53](https://github.com/user-attachments/assets/38875ee9-79e8-447c-9fcf-aaadc19a6ba2)
```
import matplotlib.pyplot as plt
x=[2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x,bins=10,color='blue',alpha=0.5)
plt.show()
```
![378769357-3b6a3ab4-fae3-4001-97b6-c93677c2c354](https://github.com/user-attachments/assets/c003c535-5284-487b-83c3-30b18b09ea0b)
```
import matplotlib.pyplot as plt
import numpy as np
np.random.seed(0)
data=np.random.normal(loc=0,scale=1,size=100)
data
```
![378769487-ba198b64-b050-489f-8e1f-21a30633bff5](https://github.com/user-attachments/assets/2f68697a-9f00-447c-b3bd-6ecc6eb5ffc0)
```
fig,ax=plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
```
![378769591-ddcd57f8-b28f-4f2b-8a9f-20acbb22d4f9](https://github.com/user-attachments/assets/d89115fa-62db-4021-8fc4-3c5378755047)
```
import matplotlib.pyplot as plt
activities=['eat','sleep','work','play']
slices=[3,7,8,6]
colors=['r','y','g','b']
plt.pie(slices,labels=activities,colors=colors,startangle=90,shadow=True,explode=(0,0,0.1,0),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
![378769725-b3ee428c-6798-4fc4-b926-d4b5d0f5face](https://github.com/user-attachments/assets/986a9356-d969-446c-afd7-b93b9ec58293)

```
labels='Python','C++','Ruby','Java'
sizes=[215,130,245,210]
colors=['gold','yellowgreen','lightcoral','lightskyblue']
explode=(0,0.4,0,0.5)

plt.pie(sizes,explode=explode,labels=labels,colors=colors,autopct="%1.1f%%",shadow=True)
plt.axis('equal')
plt.show()
```
![378769820-e3455128-80c6-4a10-bd16-7015cae0c291](https://github.com/user-attachments/assets/010abbce-3c08-4b6d-a4d2-8c8bcfc9bd79)





# Result:
To Perform Data Visualization using matplot python library for the given datas is successful.
