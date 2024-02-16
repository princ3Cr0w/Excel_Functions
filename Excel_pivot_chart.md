## IT operational analysis using Excel to pinpoint Windows application crashing issues
## Task:
<br>
<li>There were multiple application crashes and hangups during the course of Oct 2023 to February 2024</li>
<li>Communicate with IT managed service team to get to the root cause</li>
<li>Ask for recommendations on how to best mitigate these instances now and in the future</li>
<br>
<h3>First cleansed and aggregated the data to compress. Then, ran a pivot table and inserted charts to analyze application runtime error within [Windows Event Viewer](https://learn.microsoft.com/en-us/shows/inside/event-viewer) which indicates crashing of some of the apps in Windows between 2023-2024 for comparison</h3>
<br>
<sup>.Net Runtime Error and Application Error had an uptick by 2024</sup>

![Snip](https://github.com/princ3Cr0w/Excel_Functions/blob/main/Screenshot%202024-02-15%20105310.png)

<sup>Overall contrast between 2023-2024 of the total instances of .Net Runtime Error, VSS, Application Error, and Security Error</sup>
<br>

<sup>Utilized slicer for itemized views</sup>
  
![Snip](https://github.com/princ3Cr0w/Excel_Functions/blob/main/Screenshot%202024-02-15%20121600.png)

<sup>Overall combined findings where VSS appears most often</sup>
![Snip](https://github.com/princ3Cr0w/Excel_Functions/blob/main/Screenshot%202024-02-16%20103957.png)

## Outcome:
<li>Communicated to engineer about my findings</li>
<li>Engineer acknowledges my hypothesis why a constant slow-downs happen</li>
<li>Engineer recommends to get Dell engineers to look closer on .Net errors</li>
<li>I recommend analyzing events on the other machines in the premise and make a batch report</li>
<li>Re-iterate analyis every quarter of the year to see any improvements/regression</li>
