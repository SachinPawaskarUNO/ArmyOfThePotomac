This folder has data files
MSHWRData: Original Data File
List of Battles-timeline: Data file created with list of battles for every month
Cleansed Disease Data : Cleaned Original Data File

This project combines a data set consisting of the cases of death by disease and month that the Army of the Potomac suffered during the civil war (MSHWR Data.xlsx) and a data set that contains the events that the Army of the Potomac participated in each month of the civil war (List of Battles-timeline.xlsx). MSHWR Data.xlsx was cleaned to change null values to zero and renamed to Cleaned Disease Data.xlsx. It was then joined to the List of Battles-timeline.xlsx in the Tableau prep file AOTP FLow.tfl. The diseases columns were then pivoted and the output was saved as Pivoted AOTP Join.xlsx. This data set was then connected to Tableau and used to create the visualizations found in the AOTP Project.twb file.
