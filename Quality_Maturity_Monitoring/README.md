# QUALITY MATURITY MONITORING SYSTEM

![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/Quality_Maturity_Monitoring/images/Main_Standard.png?raw=true)

> This Appliaction is buit to handle the Quality issues faced by user during TOUT stage and to assign that issue to concerned team using web interface.
***
### <u>Objective</u>
 * To develop an online sytem for Quality Monitoring,
 * <b>Remove Old Paper Based</b> Life Cycle,
 * <b>PLM Integration</b> for Providing real time Tracking of Quality checks,
 * Consolidated Dashboard for Quick Overview of Quality Checks
***
### <u>Life Cycle</u>

> This Application is divided in 5 stages which are as below:

![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/Quality_Maturity_Monitoring/images/Life_Cycle.JPG?raw=true)

> 1. User Mapping
> 2. Create Feedback
> 3. Close Feedback
> 4. Verify Feedback
> 5. Status Tracker
***
## Short Description of Stages
> ### <u>1. User Mapping</u>
Using this module Quality Head assign received / Identified quality issue to a supervisor.
 Below image represents the Supervispor assignment Dashboard <br>
 
![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/Quality_Maturity_Monitoring/images/ownerMapping.JPG?raw=true)

> ### <u>2. Create Feedback</u>

  Post Supervisor allocation, as an Owner, he <b>add the Quality Issue </b>recived through this module and here<b> for one work order Multiple Issues will be added with different serial number (auto generated).</b><br>
  Once Created <b>Mail goes to the Concerned who works on that Serial No.</b> <br>
  
  ![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/Quality_Maturity_Monitoring/images/CreateFB.JPG?raw=true)

> ### <u>3. Close Feedback</u> 

 This is the stage where the person who resolved the Created Feedback assigned to its name will have to <b>update and close</b> it in Portal, while closing Feedback Solution <b>Image is mandatory</b>.<br>
  Once Saved <b>Mail triggers to the Owner</b> for <b>verification and acceptance</b><br>
  
 ![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/Quality_Maturity_Monitoring/images/Closure_FB.JPG?raw=true) 
 
 > ### <u>4. Verify Feedback</u>
 
 In this stage the Feedback <b>Supervisor/Owner have to Accept or Reject</b> the given Solution in previous stage. If <b>Rejected Mail triggers to the Solver</b> for rework with suitable Reason of rejection. Else Feebcak is considerd as Closed.<br>
> During Verification Records has been <b>fetched form PLM using PERL SCRIPT </b>so that <b>Actual tracking</b> will be done and <b>Human intervention is eleminated</b><br>

 ![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/Quality_Maturity_Monitoring/images/VerifyFB.JPG?raw=true)
 
 > ### <u>5. Status Tracker</u>
 
 This Dashboard <b>shows all records</b> which are Raised by the Supervisor and Quality team <b>for Tracking the current status</b>. This Dashboard <b>uses Datatable Plugin</b> for<b> Quick Search and to filter specific record through serach box.</b><br>
 
 ![enter image description here](https://github.com/ankesh-verma/PERL/blob/main/Quality_Maturity_Monitoring/images/TrackWindowFB.JPG?raw=true)
