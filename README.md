Disclaimer: This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY that it will perform flawlessly or be fit for a particular purpose. The use or mention by NIST of commercial products does not imply endorsement or indication that they are the only, or best, products. 

Purpose of this program
This program allows collection of information about gene editing operations and activities performed on transfected cells. It allows tracking of what is done and when to individual cell samples over time.
   
Instructions for using Transfection Tracker
Transfection Tracker_v2.0520.xlsm 

Overview: 
•	This program was created in Microsoft Excel for Microsoft 365 MSO (16.0.13127.21490) 32-bit.
•	The program is composed of interrelated worksheets. Worksheets include Calendar, Metadata Template, Cell Samples, Activity List, Data Validation Criteria, and Documentation.  
•	Bold lettering indicates the name of a worksheet.  Bold Italics indicates an input available on a worksheet.  Italics indicates a choice of input. Underline indicates examples of free text.	
•	Refer to the Documentation worksheet within the program for additional specific information.

1.	On opening the program, Enable Editing, Enable Content, Update Connections (don’t worry about a failure here).  If you intend to add data, answer NO if you see a question to open in ReadOnly mode.	
2.	The Calendar worksheet allows entry of activities performed on each sample for any date. 
3.	From the Calendar worksheet, use drop-down features to select Cell Sample Name and Activity from drop-down lists. 
a.	Activity Transfect initiates creation of a new transfection Metadata Template worksheet. User can choose a previous template to modify. The date is automatically entered on the Template, a transfection designator (cell A44 on the worksheet) is assigned by concatenating data entered about the transfection, and the worksheet is automatically renamed with the transfection designator.  A folder named with the transfection designator can also be automatically created within the operating system.** 
b.	When a clone is identified, choose the button to the right of the date to Designate New Clone.  A drop-down menu appears from which a selection from cell sample names can be made, followed by a free text window to assign a Clone ID, which is generally a position on a multi-well plate.  The Clone ID will be appended to the cell sample name and the new name will be added to the Cell Sample worksheet and appear in the drop-down list.  A new subfolder designated with the clone ID can be created in the folder created for the transfection designator.**

4.	Use columns labeled # and Plate to type in # of wells and total wells in cell culture plate for the resulting Activity.  Exceptions to this: 								
         1.	number of 10cm plates							
         2.	number of vials for freezing	
         3.	number of flasks of size (T125)	

5.	Select Activity Discontinue when no versions of that clone are being carried further because of loss of fluorescence or other reason. Add reason to the Notes column as free text.
6.	The Activity Thaw applies only to cells from a bank previously subjected to Activity Freeze.  If you take a sample from the bank, indicate Activity Thaw.  This might be followed by Activity ExtractDNA. 
a.	A Thaw event increments passage number.

7.	Activity Sort will append the Cell Samples worksheet with a new cell sample name to indicate sort number (_S#).  This new name will appear in the Cell Sample Name drop-down list on the Calendar.  This action can also initiate the creation of a new folder with the appended name in the appropriate Transfection folder.**  
a.	Details of Activity Sort can be captured as free text in adjacent Notes column.
b.	Performing an Activity Sort increments passage number. 

8.	Other worksheets:
a.	Existing cell sample names are listed in worksheet Cell Samples.						All activities are listed in worksheet Activity List.
b.	Tabulated data are in worksheet Data.		
c.	Reports are generated in …Report worksheets.
d.	An example Transfection Metadata worksheet that was created for a specific transfection. 
e.	**The Documentation worksheet contains information that directs the automatic creation of folders and files with human readable names on a network drive.  

9.	Do NOT: 
a.	…Type in a cell line or activity into a cell on the Calendar. Choose only options in the drop-down lists. If additions to the drop-down lists are needed, add them in the Data Validation worksheet.
b.	…Insert a line, column or cell into the Calendar.	



<!---

--->
