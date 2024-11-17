# A Multi-Measure Unit Converter with GUI
- App Designed and Developed By: Adebayo Onajoko
- Programming Language Used: Python (Jupyter Notebook Environment)
- Python Libraries Used for building the App: Pandas and Tkinter


Brief Description of the Application:
=====================================
This application is a multi-measure Unit Converter that was designed to convert units for different measures. 
The measures included are time, mass, length, volume, speed, area, fuel consumption and digital storage.          
The conversion is made possible by utilizing Pandas library to read from the unitconverter.xlsx (Conversion Chart) that 
contains the 7 different measures, the various units and the corresponding conversion rates between the units.              
The App was developed using Python language in Jupyter Notebook and the Tkinter library was used for the App GUI.

The original look of the App can be seen in the screenshot below:
<p align = "center">
<img src= "https://i.imgur.com/zgX0Xrf.png",width="50",height ="50",alt="Original Look"/)
<br/>
</p>

The Steps for using the Unit Converter App:
===========================================
In order to understand how the App works, let’s briefly use a mass conversion of 100.25Kg to Pounds(lb.) as a case study.                                                                                                                                    The steps to carry out the conversion of the case above are as follows:
- Choose the measure of interest from the measure dropdown box from the available 7 and in the above case study, mass is
selected from the measure dropdown box.
- Enter the scalar quantity you wish to convert – for the case under consideration, a numerical value of 100.25 is entered
into the "Qty to Convert" box 
- Select Kilogram from the "Convert From " dropdown box and select Pound from the "Convert To" dropdown box
- Click on the "CONVERT” button.

The look of the App before clicking on the "CONVERT” button is shown in the screenshot below:
<p align = "center">
<img src= "https://i.imgur.com/uRrQqpx.png",width="50",height ="50",alt="Before Clicking CONVERT"/)      
<br/>
</p>

On the other hand,the look of the App after clicking on the "CONVERT” button is as shown below:

<p align = "center">
<img src= "https://i.imgur.com/lsdhosR.png",width="50",height ="50",alt="After Clicking CONVERT"/)
<br/>
</p>

In order to carry out a different unit conversion- choose a different measure, enter the numerical quantity you intend 
to convert, select the unit you want to convert from and the unit you want to convert to and then click the "CONVERT" button
or you just click on the "CLEAR" button which clears all the present inputs and the App is then ready for a new set of inputs.

Exception handling feature of the App:
======================================
The App is also equipped with exception handling features which enables the App to catch exceptions such as wrong combination 
of inputs into the App or inputting a non-numerical value into the "Qty to Covert" box which is meant to accept only integers or floating numbers. The above exception handling cases are captured in the screenshots below:

<p align = "center">
<img src= "https://i.imgur.com/9LZPfUB.png",width="50",height ="50",alt="Invalid or Incomplete Values"/)
<br/>
</p>


<p align = "center">
<img src= "https://i.imgur.com/vEHnE1q.png",width="50",height ="50",alt="Enter Numerial Values"/)
<br/>
</p>

<p align = "center">
<img src= "[https://i.imgur.com/vEHnE1q.png](https://i.imgur.com/9GRiPgw.png)",width="50",height ="50",alt="Enter Numerial Values"/)
<br/>
</p>

https://i.imgur.com/9GRiPgw.png


Final word on the use of the App:
=================================
It should be noted that the App can only be replicated in its full capacity if the Jupyter Notebook file, the excel 
worksheet (conversion chart) and all the necessary image files are all in the same directory.





