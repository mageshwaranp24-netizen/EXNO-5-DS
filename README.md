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

%matplotlib inline
import numpy as np
## Simple Examples

x=np.arange(0,10)
y=np.arange(11,21)

a=np.arange(40,50)
b=np.arange(50,60)

##plotting using matplotlib 

##plt scatter

plt.scatter(x,y,c='g')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')


y=x*x
## plt plot

plt.plot(x,y,'r*',linestyle='dashed',linewidth=2, markersize=12)
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.title('2d Diagram')
plt.show()
## Creating Subplots

plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
plt.show()

x = np.arange(1,11) 
y = 3 * x + 5 
plt.title("Matplotlib demo") 
plt.xlabel("x axis caption") 
plt.ylabel("y axis caption") 
plt.plot(x,y) 
plt.show()
np.pi
# Compute the x and y coordinates for points on a sine curve 
x = np.arange(0, 4 * np.pi, 0.1) 
y = np.sin(x) 
plt.title("sine wave form") 

# Plot the points using matplotlib 
plt.plot(x, y) 
plt.show() 
#Subplot()
# Compute the x and y coordinates for points on sine and cosine curves 
x = np.arange(0, 5 * np.pi, 0.1) 
y_sin = np.sin(x) 
y_cos = np.cos(x)  
   
# Set up a subplot grid that has height 2 and width 1, 
# and set the first such subplot as active. 
plt.subplot(2, 1, 1)
   
# Make the first plot 
plt.plot(x, y_sin,'r--') 
plt.title('Sine')  
   
# Set the second subplot as active, and make the second plot. 
plt.subplot(2, 1, 2) 
plt.plot(x, y_cos,'g--') 
plt.title('Cosine')  
   
# Show the figure. 
plt.show()
## Bar plot

x = [2,8,10] 
y = [11,16,9]  

x2 = [3,9,11] 
y2 = [6,15,7] 
plt.bar(x, y) 
plt.bar(x2, y2, color = 'g') 
plt.title('Bar graph') 
plt.ylabel('Y axis') 
plt.xlabel('X axis')  

plt.show()
a = np.array([22,87,5,43,56,73,55,54,11,20,51,5,79,31,27]) 
plt.hist(a) 
plt.title("histogram") 
plt.show()
data = [np.random.normal(0, std, 100) for std in range(1, 4)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=False);  
plt.show()
data = [np.random.normal(0, std, 100) for std in range(1, 4)]

# rectangular box plot
plt.boxplot(data,vert=True,patch_artist=True);
plt.show() 
data
# Data to plot
labels = 'Python', 'C++', 'Ruby', 'Java'
sizes = [215, 130, 245, 210]
colors = ['gold', 'yellowgreen', 'lightcoral', 'lightskyblue']
explode = (0.4, 0, 0, 0)  # explode 1st slice

# Plot
plt.pie(sizes, explode=explode, labels=labels, colors=colors,
autopct='%1.1f%%', shadow=False)

plt.axis('equal')
plt.show()

```

# Result:

<img width="1920" height="1080" alt="Screenshot (192)" src="https://github.com/user-attachments/assets/5536e1c9-ed09-4e04-a49c-34bd451b0402" />
<img width="1920" height="1080" alt="Screenshot (193)" src="https://github.com/user-attachments/assets/272bcb07-634b-42f5-beaf-520b4c3f498b" />
<img width="1920" height="1080" alt="Screenshot (194)" src="https://github.com/user-attachments/assets/708f5aa3-147f-4ca4-90a0-5d5e2fbef5bd" />
<img width="1920" height="1080" alt="Screenshot (195)" src="https://github.com/user-attachments/assets/1dd94b6e-d519-4941-8970-ae3ae7e5a38f" />
<img width="1920" height="1080" alt="Screenshot (196)" src="https://github.com/user-attachments/assets/75cbf5cd-0b6b-477e-9724-bd07bb61e026" />
<img width="1920" height="1080" alt="Screenshot (197)" src="https://github.com/user-attachments/assets/8e05f852-a91f-48ea-b68c-915885892068" />
<img width="1920" height="1080" alt="Screenshot (198)" src="https://github.com/user-attachments/assets/4297a283-2912-4c9d-b08b-9ecdd98b4571" />
<img width="1920" height="1080" alt="Screenshot (199)" src="https://github.com/user-attachments/assets/dd45ff9f-fec9-44eb-b4b7-22f596fc1f8b" />
<img width="1920" height="1080" alt="Screenshot (200)" src="https://github.com/user-attachments/assets/2b1e367e-ab94-426b-a995-eecb3c5e3385" />
<img width="1920" height="1080" alt="Screenshot (201)" src="https://github.com/user-attachments/assets/175b0205-9866-4de6-a26d-868c7a492d32" />
<img width="1920" height="1080" alt="Screenshot (202)" src="https://github.com/user-attachments/assets/18b4fbb6-2abf-4521-ac62-94fe552579f3" />







 
