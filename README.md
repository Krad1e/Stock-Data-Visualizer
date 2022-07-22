# Team 2 Stock Data Visualizer with Unit Testing

NOTE - MUST INSTALL THE FOLLOWING MODULES TO RUN THE PROGRAM:

API Querying - Requests

Graphing - pygal

Displaying of Results - lxml



*****Once all Modules are installed you can run the code by running Main.py*****





This project is divided into several modules: 


.Front End

  ..FrontEnd.py - This will be a command line tool to get the required parameters from the user.

.mod7_atbhz7 

  ..mod7_atbhz7.py - This file will consist of required unit testing integrated into file.
  
.API Querying 

  ..APIQuery.py - This will be the module will provide a class that will allow for input from the front end and then will query the API for the sought after data. 
  
.Filtering Results

  ..DataFilter.py - If results are not filterable through the API querying this module will be necessary to filter the results. 
  
.Graphing Results

  ..ResultGraphing.py - This will take the results from the query or from the filtering and will graph them using pygal. Then using lxml will render the results into a web browser. 
  
.Main

  ..Main.py - Main will bring everything together and will be the script to run the program.  
