## **Getting Started in SAP Central Business Configuration (CBC)** 

**Abstract:** 

SAP Central Business Configuration enables you to scope, configure, and implement end-to-end business processes for your cloud solution from a central place. 

Key Features:
- Intuitive on-screen guidance of your activities
- Customer-driven changes
- Scoping with increased flexibility and reduced processing time
- Guided and flexible setup of the organizational structure
- Embedded help for instant user assistance

                                                         
>More information can be found in SAP Central Business Configuration in-app help by starting the Quick Tour. 

At this point the handover of business scope from sales team to the implementation team is done and implementation can start using SAP Central Business Configuration.

Workspace have been already precreated in the system for the excersie, nevertheless in a real implementaion you need to create the workspaces based on the system type: evaluation workspace to connect to starter system or/and implementation workspace to connect to the development system. More information on create workspaces can be found here: [Workspace Management](https://help.sap.com/docs/CENTRAL_BUSINESS_CONFIGURATION/55c9333eed324cd284f6c4e5dab8462f/c38f719c010d4191bb8f1cf8135f12f2.html?locale=en-US&version=LATEST).


**Exercise:**

1. Open [SAP Central Business Configuration](https://my90267828.trn01.cbc.eu.one.cloud.sap/) in a new browser tab. 

2. Log on with the user credentials provided.  

>Note: The workspace is already available, and you have been assigned as a team member to start the implementation. 


>*Assign Deployment Target* activity has been already completed for your workspace. You can view it or set it to *Completed*. In this step the connection between SAP Central Business Configuration workspace and S/4HANA tenant is done. 

3.	Open *Define Scope*.
>Note: You can perform scoping  directly in the app or by importing a file that can be downloaded from the digital discovery assessment (DDA) tool. Either way, it’s recommended to implement no more than 5 countries/regions per wave. Scoping application will ensure that any dependencies or inconsistencies between the scenarios are considered. 
4.	In the *Select Country/Region* dialog box, choose *Import Scope from JSON File*. Then, choose *Browse*.
5.	Select the provided scope file and choose *Import*.
>Note: A warning message may be issued in case the Digital Discovery Assessment was done using a content version which is different than the one of the workspace. This is ok as DDA is usually done months before (even in a previous release) the actual implementation start in SAP Central Business Configuration. You can check the content version in the user profile in the *About* section. </br> 
6.	Check for rejected scenarios and warnings.
>Business Context: Rejected scenarios can only be added via a support case, whereas scenarios with a warning can be added directly by acknowledging the warning message. You can download a list of the rejected scenarios and attach it to the support case.
7.	Choose *Confirm and Import*. 
8.	Adapt your scope further by adding a group ledger scenario. To do so, search for IFRS and add the *Accounting and Financial Close – Group Ledger IFRS (1GA)* scenario to scope. 
>Note: Group ledger scenarios can only be added in the initial scoping. 
9.	Open the *Selection Allowed* dropdown list and select *Initial Scoping Only*.
>Note: The scenarios displayed are only available for selection during the initial scoping and cannot be added later in scope extension. You can go ahead and select any of these scenarios in addition.
10.	Open the *Selection Allowed* dropdown list and select *All*. 
11.	Select *Germany* from the *Countries/Regions* filter and add a scenario just for Germany (for example, *Predictive Accounting for Sales Orders (2FD)*).
>Note: Scenarios with a lock icon can only be added via a support case under component XX-S4C-OPR-SRV, whereas scenarios with a warning can be added directly by acknowledging the warning message.
12. Select *All Countries/Regions* from the *Countries/Regions* filter to view the scope available for all countries again.
13.	Choose *Select Countries/Regions*.
14.	Choose *More Countries/Regions* to select a non-standard country in addition. 
>Note: Non-standard countries (countries which do not have an SAP-delivered local version) can be implemented via the Configuration Localization Tool embedded within SAP Central Business Configuration. 
15.	Choose a target country/region (for example, *Cook Islands*) and *Germany* as source country/region.
>Note: Germany is currently the only available source country/region.
16.	Choose *Create Target Country/Region* and confirm the caution note. 
>Note: Non-standard countries can only be added if no countries/regions have been implemented so far (during the initial scoping). In case there are countries/regions already activated; the parallel line feature needs to be used to implement the non-standard country/region.
17. Enter "localization" key word in the search bar. Sceanrios 7VW and 7WP are shown. Add one of them to scope.
>Business Context: Sceanrios *Bill of Exchange for Configuration Localization Tool (7VW)* and *Withholding Taxes for Configuration Localization Tool (7WP)* are new scenarios available only for non-standard countries and are based on source country Spain. They can be added in addition to your non-standard country. They serve the purpose to meet other localization requirements which go beyond the scope of source country Germany. They are optional and can be selected if the processes are required in the non-standard country you are implementing. 
18.	Explore the scope of the non-standard country using *My Selected Scope*.
>Note: Your selected scope is grouped by line of business. You can download it in pdf format, add comments, or filter it by country/region
With this, you have completed the exercise. 
>Note: In a real implementation you would *Complete Activity* and then continue with the next activities which will appear in the list to move on in your implementation. You can practice scope completion in [Define Scope](https://education.hana.ondemand.com/education/pub/cbc/index.html?show=project!PR_4E5C20A1C2A9228F:uebung#TS_F1FF49E31A904BB69D0BB3B403C55C38) tutorial. 


**To learn more:** 
- [Scoping](https://help.sap.com/docs/CENTRAL_BUSINESS_CONFIGURATION/55c9333eed324cd284f6c4e5dab8462f/e5be8601ba024fff90beeae29f52e20c.html?locale=en-US&version=LATEST) documentation on SAP Help Portal
- [Configuration Localization Tool](https://help.sap.com/docs/CENTRAL_BUSINESS_CONFIGURATION/55c9333eed324cd284f6c4e5dab8462f/d208986de8c0407abbe242847ccf1487.html) documentation on SAP Help Portal
- [Configuration Localization Tool Restrictions and Limitations](https://me.sap.com/notes/3107866)
- [Import Scope](https://education.hana.ondemand.com/education/pub/cbc/index.html?show=project%21PR_4CF48037E39416B7:uebung) as interactive tutorial or PDF 
- [Import Scope](https://help.sap.com/docs/CENTRAL_BUSINESS_CONFIGURATION/55c9333eed324cd284f6c4e5dab8462f/4d6edb7e901c401bbafcd42ab06f2866.html?locale=en-US) documentation on SAP Help Portal




