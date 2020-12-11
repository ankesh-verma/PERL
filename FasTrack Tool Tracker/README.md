## FasTrack - PE Tool Tracking System

![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/FasTrack%20Tool%20Tracker/images/Die_lifeCycle.png?raw=true)

> This Project is built to have an integrated system across all types of tools for all LOB's with a single login access and views based on the user roles.
***
### <u>Objective</u>
 * Monitoring work order movement over its entire life cycle till production handover,
 * Data management with checks against PLM data and facilitation of tool history, inspection reports and tool handover reports,
 * SAP integration for Plan vs Actual Cost and Hour check for all work orders,
 * Introduction of panel level phase and cascade it to WO level phase with interdependency of stages  to follow established process 
***
### Description :
FasTrack is a system through which all tool and DIE related information is available online and can be accessed from anywhere within client's network.
Before this project, data was being managed by all different stakeholders using MS Excel and there was great dependency on individual person to get any information for any TOOL / DIE.

FasTrack is mainly  divided in Three Parts:
 1. Pre-Planning [Panel Level Data Management], 
 2. Design [WO Release Level] and 
 3. Design to HLTO [Schedule from Design to HLTO]. 

This system is also integrated with PLM and SAP for data updation for different Stages of tools/DIE's life cycle.
Using different Summary reports (LOB based), ongoing Projects, Section wise work order being issued and their stage status and month wise 
Planned Vs Actual records for hours and cost getting tracked.In addition it involves reports of work order's which are lagging at which stage, cost & hours related reports generation for all projects as well as section wise Live Load Information for each Sections WOs.

Using line chart and bar chart user is able to monitor development in much effective way.
 
***
## FasTrack Life Cycle
> FasTrack Life cycle consists of steps as:
![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/FasTrack%20Tool%20Tracker/images/FTS_LifeCycle.JPG?raw=true)
1. Panel Upload
2. Allocate Operation
3. Upload Schedule
4. Work Order Allocation
5. SAP and PLM record capturing
6. Tracking Dashboards
***
1. <b>Panel Upload :</b>
     
![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/FasTrack%20Tool%20Tracker/images/uploadPanel.PNG?raw=true)
*   In this Step Planner has to upload the Panel against Project and Its Component Number, This consist of Plan dates of various Stages (Simulation, Material Planning and Offload type), Post upload it will be searched through Search dashboard.
 2. <b>Allocate Operation :</b><br>
    ![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/FasTrack%20Tool%20Tracker/images/Operation.PNG?raw=true)
   * Design Group leader for Uploaded panel have to define operation steps and allocate designer.<br>
3. <b>Upload Schedule :</b>
      * In this step planner will add schedule plan dates for every stages ,i.e. Design, Preparation, Assembly, Tryout, HLTO; and Planned cost/hour against defined operation.<br> 
4. <b>Work Order Allocation :</b>
      * In this step Planner has to allocate actual work order for every operation defined by   group leader in step 2.<br>
5. <b>SAP and PLM record capturing :</b>
      * To get actual completion date of stages as well as actual cost /hour taken per stage PLM and SAP integration done using PERL scripts. Every time when dates, cost and hour's updated in SAP/PLM PERL script will capture it and update actual column in FasTrack.  <br>
6. <b>Tracking Dashboard :</b>

![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/FasTrack%20Tool%20Tracker/images/EQAP.PNG?raw=true)
 
   * To track progress in DIE making various line plot as well as bar plots has created for better visualization and easy understanding. Along with summary dashboard's has been made that shows Live load month-wise/section-wise, which ever user wants to track.

* For more details click here
  
