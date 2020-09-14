CONVID-19 Simulator:
=======================

Thanks for using CONVID-19 Simulator.

Steps to run the software:
---------------------------

Prerequisite:
-------------
JRE version 1.8 or higher need to be installed and associated with the *.jar files.

Step 1: Extract the Binary.zip file into any directory.
Step 2: Run the COVID-19 Simulator.jar
Step 3: Login to the privileged user mode, press the Login button.
		Default username: admin
		Default password: admin
	You can update is if you want later on.
Step 4: Download latest data file from https://raw.githubusercontent.com/datasets/covid-19/master/data/worldwide-aggregated.csv
Step 5: Press Import Data button and choose the downloaded CSV file to load the data into the system. It will take several minutes, based on system performance.

Now the system is ready for simulation. As we have distributed the database script along with the binary package, Step 4, 5 are optional.

Press View Report button to get printable report, choose desired date range and press Ok
Press View Chart button to display Line chart, choose desired date range and press Ok

Admin user can Add and Update Patient information based on patient ID.

For example, to Update patient information
1. Press Update patient Info
2. Enter an ID between 0 to around 100000, press Search button in the dialog
3. Update the patient's names and test date as required
4. Press Ok button to save, confirm dialog will be appeared

If you want to verify whether the data is actually updated or not, Load the patient information in the same update patient dialog.
Updated data will be displayed

Steps to continue development:
------------------------------
This is a eclipse Java Project which includes all required libraries.
Just you need extract the Source.zip and open the project in Eclipse and continue development.

Test driver is a part of the project which contains all automated test cases using JUnit