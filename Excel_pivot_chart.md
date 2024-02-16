## IT operational analysis using Excel to pinpoint Windows applications crashing issues
- [Task](#task)
- [Process](#process)
- [Analysis](#analysis)
- [Visualization](#visualization)
- [Outcome](#outcome)
- [Recommendation](#recommendation)
## Task:
<br>
<li>There were multiple application crashes and hangups during the course of Oct 2023 to February 2024</li>
<li>Communicate with IT managed service engineers to get to the root cause</li>
<li>Ask for recommendations on how to best mitigate these instances now and in the future</li>
<br>

## Process:
1.Accessed Event Manager (source) and filtered data showing errors, critical, and warning status only
<br>
2.Exported filtered data in .CSV format
<br>
3.First cleansed and aggregated the data to compress the variables. Then, ran a pivot table and inserted charts to analyze application runtime error within [Windows Event Viewer](https://learn.microsoft.com/en-us/shows/inside/event-viewer) which indicates crashing of some of the apps in Windows between 2023-2024 for comparison<br>
4.After successfully running pivot tables and plugging the event IDs, changed the value field settings to COUNT the event ID variables 
<br>
## Visualization in pivot table worksheet
<sup>.Net Runtime Error and Application Error had an uptick by 2024</sup>

![Snip](https://github.com/princ3Cr0w/Excel_Functions/blob/main/Screenshot%202024-02-15%20105310.png)

<sup>Overall contrast between 2023-2024 of the total instances of .Net Runtime Error, VSS, Application Error, and Security Error</sup>
<br>

<sup>Utilized slicer for itemized views</sup>
  
![Snip](https://github.com/princ3Cr0w/Excel_Functions/blob/main/Screenshot%202024-02-15%20121600.png)

<sup>Overall combined findings where VSS appears most often</sup>
![Snip](https://github.com/princ3Cr0w/Excel_Functions/blob/main/Screenshot%202024-02-16%20103957.png)

<sup>Combined years over time (plot)</sup><br>
<sub>Orange (2024) Blue (2023)</sub>
![Snip](https://github.com/princ3Cr0w/Excel_Functions/blob/main/Screenshot%202024-02-16%20151730.png)

## Outcome:
<li>Communicated to engineer about my findings</li>
<li>Engineer acknowledges my hypothesis why a constant slow-downs happen</li>
<li>Engineer recommends to get Dell engineers to look closer on .Net errors</li>


## Recommendation/s:
<li>I recommend analyzing events on the other machines in the premise and make a batch report</li>
<li>Re-iterate analysis every quarter of the year to see any improvements/regression</li>
<li>Run security measures if backend applications are compromised</li>
<br>

>[!NOTE]
> This project was in real-time root-cause analysis in the premises using actual source* and machines in Microsoft 365 Environment
<br>

>[!Important]
>*No sensitive data enclosed in this analysis

