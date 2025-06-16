# DSA DOCUMENTATIONS 
**TUTOR**: Mushin Hameed
## Introduction to Data analysis                      
![DSA 1](https://github.com/user-attachments/assets/8f1378cb-2120-46ec-9e62-ccfb1c126f84)

### What is Data Literacy


Data Generation: is the ways that organisation gather data
organisation run on two systems. 

- Operational systems

Execute buiness process: off the shelf Systems SAP,Oracle, Dynamics 365, Zoom

- Analytic systems

Evaluate Business process: Self-Service BI tools Like Power BI
![2](https://github.com/user-attachments/assets/de9d6f63-2a1a-4d8f-b094-96d4fc92094d)

### Data Storage


- On Premises: Data stays within the organisation 

- Cloud: Data is sitting outside the organisation eg. Asure, Google Drive e.t.c

### Data Sources 
this are place where data can be retrived 

![3](https://github.com/user-attachments/assets/ea6d9217-2bb4-4f0b-bb82-8405305daab2)


### Data Structure 

![4](https://github.com/user-attachments/assets/3d7e01ed-6482-4754-a4aa-563cf9a2101c)


- Structure: Data that can fit into a table

- Semi Structure csv are semi structured 

- Unstructure e.g vedios, Images 

### Data Analysis 
![5](https://github.com/user-attachments/assets/0cb1ee28-1b2a-4505-a97f-504ec003137e)


- Ingestion: is connecting the data to your analytics tool

- Transfrom: is Remove what you dont need in the data 

- Modeling: this finding relationship betweeen different data table 

- Visualisation: putting your data into chart and graph

- Analysis

- Presentation 

### Why do business run Analysis

- What is working
- what is not working
- whate we should focus on


## EXCEL FUNCTIONS

1. Rows: are the numbers **Total Numbers rows in Excel 1048576**

2. Columns: are the latters **Total Numbers column in Excel 16384**

3. Cell: this is the intercept of rows and columns 

4. Name Box: tells you position you are in excel 

5. Formula Bar: the box in front of the name box it display calculations

   ![11](https://github.com/user-attachments/assets/b27fe011-7d3f-4d9b-b1ed-63d92a36b351)

### FUNCTIONS 


![13](https://github.com/user-attachments/assets/1316f6e5-7daa-45af-b9c4-faaa8d26267d)

Sum function is use to add numbers from different cell
```
=SUM(D8:D27)
```

Average function which is also known as the mean 
```
=Average(D8:D27)
```

To find the largest salary
```
=Max(D8:D27)
```

Lowest of salary
```
=Min(D8:D27)
```

Fourth Highest Salary
```
=Large(D8:D27)
```

Third Lowest Salary
```
=Small(D8:D27,3)
```

##### The data below shows the Company lost their Data and where able to retrive Numbers.

![01](https://github.com/user-attachments/assets/acb9bd41-820a-47ea-8e9e-33040f59ef11)


![02](https://github.com/user-attachments/assets/f304df7e-12b4-4ead-aff0-af56251c239c)


To seperate this numbers Left, Right and Mid functions will be used 

- Left: Returns specific numbers of characters from the starting of the text strings
```
=left(Text,[num_chars])
```

- Right: Returns specific numbers of characters from the end of the text strings
 ```
  =Right(Text,[num_chars])
```

- Mid:  Returns the character of the  middle of a text string, at a giving position and length
  ```
  =Right(Text,start_chars,Num_chars)
  ```

#### TEXT CLEANING 

The names are inconsistent to correct this in consistency 

![03](https://github.com/user-attachments/assets/9b1d9cf9-e590-41ea-9642-cb723a769564)


1. Eliminate Unnecessary Space from Names
    ```
   =Trim(C6)
   ```
    
2. Names written in Upper case
   ```
   =Upper(C6)
   ```

3. Names written in Lower case
   ```
   =Lower(C6)
   ```
4. Names properly Entered
   ```
   =Proper
   ```

5. Names Properly Entered and Trimmed
   ```
   =Proper(Trim(C6))
   ```

6. Company Names Properly Entered
   ```
   =Upper(E6)
   ```

#### TEXT CLEANING 2

![04](https://github.com/user-attachments/assets/8cc5a152-169c-44ab-bb23-28a03a740017)


To split text type the text the way you want it to be on the cell then click on the next cell then press **Ctrl+E**

First Name with Email
```
=CONCATENATE([@NAMES]&$E$4)
```
     
   **  OR**

```
=[@[First Name]]&$E$4
```


#### FUNCTION 3

IF function Return one value if the condiction is true and another value if the condiction is false
==========picture 06===============

Below is the score of student grade between two subject math and english
========picture 07=========

- **And** function returns true if the condictions are true
  ```
  =And(condiction 1, condiction 2)
  ```

  for the data above the condiction for a student to pass a subject is that the student must have **50** or more the **50** in each subject,

  **NOTE:** That and function will only return True or False in order to make it more dynamic we will be nesting it with **IF** function
   ```
   =if(And(condiction 1, condiction 2),Value if True, Value if False)
   ```

- **OR** Returns True if one of the condiction is meet
  ```
  =OR(condiction 1, condiction 2)
  ```

**NOTE:** That and function will only return True or False in order to make it more dynamic we will be nesting it with **IF** function
  

  




 

 
















