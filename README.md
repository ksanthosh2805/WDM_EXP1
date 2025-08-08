### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name string
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric

@data
'Jon Snow',01,low,2,male,250311
'Sansa Stark',02,high,3,female,251665
'Tyrion Lannister',03,medium,1,male,240238
'Daenerys Targaryan',04,low,5,female,200200
'Robb Stark',05,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
<img width="740" height="234" alt="Screenshot 2025-08-08 105700" src="https://github.com/user-attachments/assets/3ce1837d-d98f-4f31-a378-b2ee58f7a00f" />

<img width="723" height="325" alt="Screenshot 2025-08-08 110230" src="https://github.com/user-attachments/assets/58efc65a-4bd5-4a91-863a-855b995182d6" />


### PREPROCESSING

### Employee:-

### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Employee.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for age.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Employee Table.
13) Save the file.
14) Click on the Edit button, it shows a new Employee Table on Weka.

### OUTPUT:
<img width="603" height="206" alt="Screenshot 2025-08-08 105822" src="https://github.com/user-attachments/assets/79ccbf59-cd12-49e6-b40a-1c2006c259f8" />

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Employee.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes phone to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Employee Table on Weka.

### OUTPUT:
<img width="937" height="230" alt="Screenshot 2025-08-08 105959" src="https://github.com/user-attachments/assets/70226651-9a84-44d7-a41d-0d315a3c6fee" />

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the all attributes to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Employee Table with normalized values on Weka.

### OUTPUT:
<img width="1231" height="269" alt="Screenshot 2025-08-08 110036" src="https://github.com/user-attachments/assets/f8450f0c-f11c-4080-b821-c722febe5b73" />


### Weather:-

#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for season.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1530" height="397" alt="Screenshot 2025-08-08 110722" src="https://github.com/user-attachments/assets/0d070278-f810-4a52-bab2-1008e1752d81" />

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes season to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
<img width="1851" height="329" alt="Screenshot 2025-08-08 110800" src="https://github.com/user-attachments/assets/67df17aa-17cf-46b6-9566-275d594afd3c" />

### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
<img width="615" height="322" alt="Screenshot 2025-08-08 110847" src="https://github.com/user-attachments/assets/7858e06b-0e75-4e81-8c10-38350c7cf824" />


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
