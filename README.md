# Change-typeguess-value-for-Excel-uplaod


In our server it is Office 2010.

Change the registry entry as below

In Windows environments, select Start ► Run and type REGEDIT to display the Registry Editor.
In the registry tree, select HKEY_LOCAL_MACHINE ► Software ► Microsoft ► Office ► 12.0 ► Access Connectivity Engine ► Engines.
Double-click the Excel node.
In the right panel, double-click the TypeGuessRows entry.
Change the value data from 8 to 0.
Click OK.
Select File ► Exit to exit the Registry Editor window.
Now the excel wont guess the row datatype since we changed the value from 8 to 0.
