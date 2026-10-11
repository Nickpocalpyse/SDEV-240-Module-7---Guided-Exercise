# SDEV-240-Module-7---Guided-Exercise

The purpose of this application is to be able to add any student with their first name, last name, program name, GPA 0-4 and ID number.  
You can use the application just by filling in the information and pressing Add Student.  This will update the grid view.  You can move the sizes of the categories from there.
You can also save it to a file using the Save to JSON button, so next time you open it using Open from JSON, you can just reload the previous information.  Using the Clear Grid button clears the grid of all info, so you can save the files to start fresh.
The program makes sure you can only enter positive IDs and names with values by ensuring a Label with errors of what is wrong.  The GPA is hard-coded to be between 0 and 4 for ease of use.  Holding down the arrows will increase it incrementally, or pressing it as well.
The JSON file is found in Module7JsonStudentRecords\Module7JsonStudentRecords\bin\Debug\net10.0-windows as students.json  
If the file is not there, then you haven't saved a JSON for it yet.  Once you save it as a JSON file, you can edit it manually if needed.
