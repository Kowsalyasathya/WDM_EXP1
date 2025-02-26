### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing

### DATE: 20.02.2025

### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing.
  
### PROCEDURE: 

1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

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

#### Employee dataset:

![416628356-1a92ad03-f3f0-4d3a-a2ce-cb0399453a5b](https://github.com/user-attachments/assets/edd2aab0-cca6-4b8d-94f1-9abc6e9fc81f)

#### Weather dataset:

![416628599-10a729d2-dd4a-45d9-aa7b-b4f5ccf4f34f](https://github.com/user-attachments/assets/e12fc1a0-5697-48d3-832a-b13233df5a32)

### PREPROCESSING

### Procedure:

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
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

#### Employee dataset:

![416628424-39c41d09-b36f-4f6f-b70e-69067a13f23f](https://github.com/user-attachments/assets/eaa04370-ff33-4543-baa3-0899eccb096d)

#### Weather dataset:

![416628632-f15ca22e-9287-4fc2-a20d-ccdec979a88d](https://github.com/user-attachments/assets/7e88d06e-6cde-499d-8181-5be3f8a14fb3)

### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

#### Employee dataset:

![416628481-dff7f1a7-5b37-49f6-b747-5ffea4b7db92](https://github.com/user-attachments/assets/6221f2e6-ae4d-4d94-baa5-3cda1ebf37a0)

#### Weather dataset:

![416628659-360165ce-ff10-4b49-88a3-35ae4af89c42](https://github.com/user-attachments/assets/396aa6c0-3f86-4c1c-97fd-c4343d5916c0)

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

#### Employee dataset:

![416628525-c9796808-bde2-496c-a8c2-44c65956554a](https://github.com/user-attachments/assets/ec70e6aa-0cbb-4f4d-90a3-8f764eb578d3)

#### Weather dataset:

![416628677-3b3aa445-2053-4137-adb7-3780893a919e](https://github.com/user-attachments/assets/a2a5da7b-dc5d-44df-8bfe-c39861e83c27)


### RESULT: 

  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
