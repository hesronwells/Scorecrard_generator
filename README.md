Hello,

Please find the steps for automated extraction of the Quality Report.

 
Step 1) Open the attached Workbook. It has 4 tabs (Please don't change name of tabs or delete any tab)

 
Quality scorecard (Tab1)


Macros will copy the new sample Quality Report from this Tab so, if you want to add something( Ex: links for calibration, Week date etc) which is common and needed to be appear in each CM Quality Report. Please Add it here once and it will copy it from here.


![](Images/1.png)




Note: Every new week when you are generating quality reports, please change Week dates(R1 cell) or else it will result in error as we are trying to generate report twice for same date


Step 2) 

Copy pastes your entire Weekly report and Internal Audit report in their respective Tabs

![](Images/2.png)

Note: If weekly report is too large to copy the entire report, add filter in appeal column and it will lower down the volume.

Step 3) Preprocess 

Use shortcut: Ctrl + p   OR   Select Macros from developer ribbon.



![](Images/3.png)
![](Images/4.png)



Macros will automatically change it format to desired format to extract data


Step 4) 

Once the data is pre-process, please select the desired macros.


1) If no previous file exists for CM

select New_qauality_report from macros 

Or use shortcut key : Ctrl + n


![](Images/5.png)


2)If the file for CM already exists and you want to make a new sheet in existing file then 

select Quality_report from macros

Or Shortcut key : Ctrl + r


![](Images/6.png)


Step 5)

Once you run either of the option from step 4, you will see command input box in which copy-paste CM email


![](Images/7.png)


Step 6)

At the end,  you will see below message box. This means macros have successfully the saved data


![](Images/7.png)


Step 7)

After you are generated Quality report for all CM. 

Select Delete from macros 

Or short-cut key : Ctrl + d 

This will delete all previous data and Make workbook clean and empty for your next week data.


![](Images/8.png)


Important Pointer While Dealing with Macros: 

1) If the Quality report file of the CM already exist and the macros to create new file it will pop up error. 

Note: On click Yes it will replace the existing file and we will lose all the previous data.

ALWAYS CLICK NO


![](Images/9.png)



2) If any Point you will see following error message. Please select END.

Restart the process again


![](Images/10.png)

If you face any problem, please feel free to contact me on linkedIn. Kudos:)


