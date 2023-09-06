# A Property Price Estimator App 
- App Designed and Developed By: Adebayo Onajoko
- Programming Language Used: Python (Jupyter Notebook Environment)
- Python Libraries Used for building the App: Pandas and Tkinter


# Brief Description of the Application:
This application is a Property Price Estimator that was designed to give a rough price estimate of a property(house) based on the 
postal code entered by the user.          
The base price of the house is retrieved by utilizing Pandas library to read from the House Price Spreadsheet(myprop.xlsx ) that 
contains the different house types in all the available Postal Codes and their corresponding price. 
However,the final price of the property would depend on the facilities selected by the user and their corresponding quantities
and the applicable property tax that was integrated into the App.            
The App was developed using Python language in Jupyter Notebook and the Tkinter library was used for the App's GUI.

The original look of the App can be seen through the link below:
https://github.com/beewhy777/Python-Projects/blob/main/PropertyPriceEstimator/screenshots/original.png

# The Steps for using the Property Price Estimator App:

The Application is really a user-friendly App.In order to get the rough market price for the area of choice,the user needs to follow
the steps enumerated below:
- User should enter the Postal Code of the area for which he or she wants to get a property.
- Select the building type of choice from the available building types.Although the available building types(bungalow,duplex and 
triplex) are just 3  for now : However,the App can easily be scaled up to accomodate more building types by a very minimal modification
of the software code.
- Enter the needed number of beds,bathrooms and garages for the property you intend to buy.
- Apart from the facilities listed in the last step above, the user has the option to choose any/all of the optional facilities(Jacuzzi,Swimming
Pool and Basement)
- Click the "ESTIMATE" button and the average market price in the area of choice would be displayed accordingly.

In order see the App in action,let's enter a postal code of "A1C1A1", select "Duplex" as the building type,4 beds,4 bathrooms,2 garages 
and check all the optional facilities and click on the "ESTIMATE" button and the outcome of the App would be as shown in the screenshot 
below. To access the screenshot,click on the link below:
https://github.com/beewhy777/Python-Projects/blob/main/PropertyPriceEstimator/screenshots/testrun.png

Reinitializing the App(i.e clearing the App Values)
===================================================
When all values for the App parameters have been entered and the outcome has been displayed and you intend to get result for a 
different set of values,click on the "ZERORIZE" button and this would clear all the last values on the App and a new set of values can then
be entered to get the new intended outcome.

Exception handling feature of the App:
======================================
The App is equipped with exception handling features which enables the App to catch exceptions such as entering a postal code that is
not available, wrong postal code or omitting any of the mandatory fields.
The above exception handling cases are captured in the screenshot which can be accessed through the link below:
https://github.com/beewhy777/Python-Projects/blob/main/PropertyPriceEstimator/screenshots/exception_handling.png



Final word on the use of the App:
=================================
It should be noted that the App can only be replicated in its full capacity if the Jupyter Notebook file, the excel 
worksheet (myprop.xlsx ') and all the necessary image files are all in the same directory.





