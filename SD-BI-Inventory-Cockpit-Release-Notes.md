## SD BI Inventory Cockpit Releases

### 5.1.2

#### Enhancements

- AppSource App - The Send Selected to Requisition Worksheet action was enhanced to include Location and Bin Code. This action is available on both the Item Alert List and the SKU Alert List.

### 5.1.1

#### Enhancements

- AppSource App - A link to the user guide on the DynamicsShop page was added to the About page and to the Manage Subscriptions page.

### 5.1.0

#### Enhancements

- AppSource App - Changes were made to the Item Alert List for the Item Inventory Implementation Setup. Multiple line selection is now allowed and a new flowfield Qty. On Requisition was surfaced on the page.

- AppSource App - Changes were made to the SKU Alert List for the SKU Inventory Implementation Setup. Multiple line selection is now allowed and a new flowfield Qty. On Requisition was surfaced on the page.

- AppSource App - A change was made to the recalculate Overstock logic in the Refresh Alerts action on the Item Alert List for the Item Inventory Implementation. Rebuild and Refresh tooltips were updated to reflect the differences in the Refresh and Rebuild actions.

- AppSource App - A change was made to the recalculate Overstock logic in the Refresh Alerts action on the SKU Alert List for the SKU Inventory Implementation. Rebuild and Refresh tooltips were updated to reflect the differences in the Refresh and Rebuild actions. 

- AppSource App - The SKU implementation now takes variants into account in the calculations.

- AppSource App - An Assisted Setup action and functionality was added to the Setup Card.

- AppSource App - A Budget Name was added to the Setup Card to allow users to choose a Budget to use in the Forecast KPIs on the Sales Trends FactBoxes.

- AppSource App - The Item Forecast Page, ID 1851, was surfaced as a FactBox in the Managed Items and Managed SKUs Lists.

- AppSource App - UI changes were made to the Inventory Cockpit Activity Panel.

- AppSource App - A new Activate Licence and Setup Wizard was created.

- AppSource App - A new action was added to the Setup Card called View Our Apps. This action opens a page on AppSource pointing to all our Simply Dynamics Ltd apps.

- AppSource App - The Lead Subscription Link from the Request Subscription action in the Product Activation page was updated.

- AppSource App - Changes were made to the Manage Subscriptions page.

- AppSource App - The notification to activate the app, displayed on fresh install of SD Inventory Cockpit, was added to the standard Business Central role centres.

### 5.0.0

#### Enhancements

- AppSource App - Functionality was added to the SD BI Inventory Cockpit to flag items as new or established determined by a Sales Period length and Dimension Codes and Values on the Item Templates.

- AppSource App - The Item Templates were extended to create new Dimension Codes and Values and a Sales Period field. These fields are stamped on an extension of the Item Card when an Item is created using the Template.

- AppSource App - A new table Item Lifecycle Log was created to store the Item code by Status, Created Date, First Sale Date, and Established Date.

- AppSource App - The first sales date and item status is stamped on the Item Lifecycle Log when the Refresh action on the Inventory Cockpit Role Centre is chosen or when a Job Queue running the SDY UTPBI Item Lifecycle Mgt. Codeunit is run. For pre existing items the Item Lifecycle Upgrade report from the Inventory Cockpit Setup Card can be run to create entries in the Item Lifecycle Log.

- AppSource App - When the Refresh action on the Inventory Cockpit Role Centre is chosen or when a Job Queue running the SDY UTPBI Item Lifecycle Mgt. Codeunit is run, SD BI Inventory Cockpit checks for first sales date versus the Sales Period and updates the item to established in the Item Lifecycle Log.

- AppSource App - An action was surfaced in the Inventory Cockpit Setup Card to run a report for initial analysis and stamp Dimension Code and Values, and Sales Period on legacy data.

- AppSource App - Two new KPI cues were surfaced on the Inventory Cockpit Role Centre for New and Established Items.

- AppSource App - The new Item Lifecycle Log page was published as an OData page.

- AppSource App - The new functionality was added to the licence controller check.

### 4.0.0

#### Enhancements

- AppSource App - Functionality was added to SD BI Inventory Cockpit to alert by SKU or by Item.

- AppSource App - New Sales Trend Functionality was added to the App. 8 KPI fields were added to a new Sales Trend FactBox.

- AppSource App - A FastTab caption on the SD BI Inventory Cockpit Setup card was recaptioned.

- AppSource App - A change was made to the Sales Trend DateFormula FastTab in the SD BI Inventory Cockpit Setup Card to display the date example of the DateFormulas Period Start and Period End by selecting the Assist Edit button beside the Period End fields. 

- AppSource App - Additional Alert Exclusions were added to the Setup Card - Ignore Blocked Items, Ignore Purchasing Blocked Items and Ignore Sales Blocked Items.

- AppSource App - If Alerts are excluded in the Setup then on Refresh or Rebuild of Alerts previously calculated Alerts and Alert Quantities are now cleared.

- AppSource App - The cues displayed in the SD BI Inventory Role Centre were added to the SD BI Inventory Cockpit Activity Panel.

- AppSource App - A Sales Trends cues FactBox was added to the Item Alert list and the SKU Alert list and placed in the first FactBox.

- AppSource App - The logic behind the Refresh Alerts calculations was reworked.

- AppSource App - The Requisition Worksheet was extended to flag those lines created by the Inventory Cockpit tables.

- AppSource App - The Links in the About Page were updated.

- AppSource App - The logo in App was updated to the new logo.

#### Bug Fixes

- AppSource App - An error was raised on renumbering an Item No. when the item was an Inventory Cockpit Managed Item.

### 3.2.3

#### Enhancements

- AppSource App - The Power BI Report FactBox was removed from the Role Centre.

### 3.2.2

#### Enhancements

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

- AppSource App - An Alert Notification was added to the SD BI Inventory Cockpit activity pages to notify users to activate the SD BI Sales Inventory licence on install of the App.

#### Bug Fixes

- AppSource App - When selecting SD BI Inventory Cockpit activity pages in the Tell Me/Search in a BCv22 environment, the activity pages were hanging.

- AppSource App - A change was made to the ISV Licence Notification procedure in SD BI Inventory Cockpit to fix an issue that would raise an error when the language is changed from English to another language.

### 3.2.1

#### Enhancements

- BCv21 App - The Licence Expiry message/notification was updated to display the App Name in the expiry message.

- BCv21 App - A page was created to display all the Simply Dynamics Apps and subscription details for the tenant.

- BCv21 App - The Licence Message on first install of the App was updated to prompt the user to activate a Free Trial.

#### Bug Fixes

- BCv21 App - A fix was made to the code for licence key checks on the SD BI Inventory Cockpit Role Centre. 

### 3.2.0

#### Enhancements

- BCv20 App - In the Item Cliff Alerts page the Item Description was updated to highlight in Red if the Item is in Alert. 

- BCv20 App - The New and Delete Actions were removed from the Alerts Group List. A change was also made to the page not to allow users update the Item Category Code on the lines. 

- BCv20 App - A small typo was fixed in the message displayed when the Rebuild Alerts action in the Items Alert list is chosen. 

- BCv20 App - The text was changed in the message displayed when the Rebuild Alerts action in the Items Alert list is chosen and the alerts are rebuilt. 

- BCv20 App - The Update Items by Item Category boolean was missing from the SD BI Inventory Cockpit Setup Card. The boolean was reinstated and updated to Update Item Alert Groups. 

- BCv20 App - The Order of the columns in the Alerts Groups list were changed to match that of the order of the default fields in the SD BI Inventory Cockpit Setup Card. 

- BCv20 App - On the Alert Groups list page, the Target Stock Cost field was changed to be noneditable.

- BCv20 App - The FastTabs in the SD BI Inventory Setup Card were renamed.

- BCv20 App - The Assisted Setup Action was removed from the BI Inventory Cockpit Setup Card. 

- BCv20 App - The Item Alerts Blocked flag was removed from the Item Alerts List as blocked items are not shown on the Managed Items Alert List. 

- BCv20 App - The Item Chart was removed from the product. 

- BCv20 App - In the Item Cliff Alerts page the fields in the Min Sales Filters FastTab were reordered. 

- BCv20 App - An Item Card action was added to the menu to allow users easy access to the Item Card from the Managed Items List. 

- BCv20 App - A small typo fix was made to some fields in the Item Alert Details FactBox. 

- BCv20 App - Changes were made to tidy up the menus in the Managed Items  List. 

- BCv20 App - A new KPIs FastTab was added to the SD BI Inventory Cockpit Setup card. 

- BCv20 App - The positions of the Managed Items and Managed Groups cue in the SD BI Inventory Cockpit Activity Panels were swapped. 

- BCv20 App - Changes were made to the Menu and Actions in the Item Cliff Alerts page. 

- BCv20 App - The caption of the Updated boolean in the Item Cliff Alerts page was changed to Refresh Required. 

- BCv20 App - A number of Tool Tips in the SD BI Inventory Setup card were updated with more user readable and descriptive tips. 

- BCv20 App - The Product Activation Page was updated to point to the new CRM URL Subscription page. 

- BCv20 App - The latest ISV Licence Controller was added to SD BI Inventory Cockpit. 

- BCv20 App - A Test App was created for AppSource Submission. 

- BCv20 App - Tooltips were added to SD BI Inventory Cockpit. 

- BCv20 App - The SD BI Inventory Cockpit App was readied for AppSource submission. 

- BCv20 App - Object Captions were updated for future translation requests. 

- BCv20 App - The Links in the About Page were updated to point at our new website. 

- BCv20 App - The latest version of the App, the AppSource URL and a URL to the product Release Notes were added to the About Page. 

- BCv20 App - Permission sets were created. 

- BCv20 App - Object names were updated to our standard ISV naming conventions. 

- BCv20 App - ToolTips were updated to point to our new website.  

#### Bug Fixes

- BCv20 App - Choosing exit on the SD BI Inventory Setup card did not close the card and the page became unresponsive and uneditable. This was fixed. 

- BCv20 App - An issue was fixed on the SD BI Inventory Setup card where choosing exit on the card did not close the card. 

- BCv20 App - A change was made to the Managed Item Alerts List to set the only editable field to the Alert Action Qty. 

- BCv20 App - If a View with an Alert Type of Average was changed to an Alert Type of Fixed, the values in the End Period were not cleared. 

- BCv20 App - In the Item Cliff Alerts page, creating a new view defaulted the default start period in the SD BI Inventory Cockpit Setup Card to the End Period in the View. 

- BCv20 App - In the Item Cliff Alerts Page when exporting the Item Cliff Alerts to excel the percentage column was missing. 

- BCv20 App - The Product Activation page was reworked to disable the Activate button unless the Product Key is filled in.

### 3.1.2

#### Enhancements

- BCv14 App - Functionality was added to the SD BI Inventory Cockpit to flag items as new or established determined by a Sales Period and Dimension Codes and Values on the Item Templates.

- BCv14 App - The Item Templates were extended to create new Dimension Codes and Values and a Sales Period field. These fields are stamped on an extension of the Item Card when an Item is created using the Template. 

- BCv14 App - A new table Item Lifecycle Log was created to store the Item code by Status, Created Date, First Sale Date, and Established Date.

- BCv14 App - The first sales date and item status is stamped on the Item Lifecycle Log when the Refresh action on the Inventory Cockpit Role Centre is chosen or when a Job Queue running the SDY UTPBI Item Lifecycle Mgt. Codeunit is run. For pre existing items the Item Lifecycle Upgrade report from the Inventory Cockpit Setup Card can be run to create entries in the Item Lifecycle Log.

- BCv14 App - When the Refresh action on the Inventory Cockpit Role Centre is chosen or when a Job Queue running the SDY UTPBI Item Lifecycle Mgt. Codeunit is run, SD BI Inventory Cockpit checks for first sales date versus the Sales Period and updates the item to established in the Item Lifecycle Log.

- BCv14 App - An action was surfaced in the Inventory Cockpit Setup Card to run a report for initial analysis and stamp Dimension Code and Values, and Sales Period on legacy data.

- BCv14 App - Two new KPI cues were surfaced on the Inventory Cockpit Role Centre for New and Established Items.

- BCv14 App - The new Item Lifecycle Log page was published as an OData page.

- BCv14 App - The new functionality was added to the licence controller check.

### 3.1.1

#### Enhancements

- BCv14 App - The Item Category Alert Group Setup was added as a Cue. 

- BCv14 App - Added a Date Filter to the Sales Period Qty field in the Item Alert Details FactBox. 

- BCv14 App - A boolean Suggest Item Category Update was added to the Setup so that when users update certain fields in the item setup they are prompted to update for all items in the same category. 

- BCv14 App - Pages were reviewed to ensure consistency of columns and and actions. 

- BCv14 App - A Refresh Required boolean was added to the Item Alerts Page under the Default View. 

- BCv14 App - A cue was added to the Role Centre to show the count of the managed items. 

- BCv14 App - The FactBox on the Item Alert List was added to all the Item Pages in SD BI Inventory Cockpit.  

- BCv14 App - Various changes were made to the Item Alert List page. 

- BCv14 App - The Refresh Alert Action was renamed to Refresh. Now when choosing the Refresh Action a dialog is presented to give the user an option to Update Data. A dialog on complete was added so the user knows the process has finished. 

- BCv14 App - Changes were made to the SD BI Inventory Cockpit Role Centre - actions were removed and cues were added. 

- BCv14 App - A change was made to the filter on the CodeUnits in the SD BI Inventory Cockpit Setup to allow users select the CodeUnits.  

- BCv14 App - The Top 10 Item Report was added to the Item Cliff Alerts page. 

- BCv14 App - In the SD BI Inventory Cockpit Setup Card, the menu actions were updated. 

- BCv14 App - The ISV Licencing Controller was added to SD BI Inventory Cockpit. 

- BCv14 App - Changes were made to the Filter FastTab. 

- BCv14 App - The Role Centre Activity Pages are now searchable from the Tell Me. 

- BCv14 App - Changes were made to the SD BI Inventory Cockpit Setup Card. 

- BCv14 App - Pages in the Tell Me were recaptioned to SD BI Inventory Cockpit. 

- BCv14 App - All objects were recaptioned to SD BI Inventory Cockpit. 

#### Bug Fixes

- BCv14 App - An issue was fixed with percentage calculations. 

- BCv14 App - Fixed error raised that Vendor No does not exist when the rebuild button in the Managed Items list was chosen/ 

- BCv14 App - Made a change to the clear out the Item Alerts Order Action Qty in the Critical Order when the Critical Order has been refreshed. 

- BCv14 App - In the Cliff Alert the first field in period needs to be start period. 

- BCv14 App - A change was made to the Critical Order List to change the Create Order action to Populate Requisition and change the Req. Worksheet to View Requisition. 

### 3.1.0

#### Enhancements

- BCv14 App - Made a publishing fix to the SD-BICI App.

### 3.0.0

#### Enhancements

- BCv14 App - Increased size of description and name from 50 to 100 as per standard D365BC change. 

- BCv14 App - Inventory Cockpit added Views, FactBoxes, Graphs. 

- BCv14 App - Functionality created to save and load views in the Alert Cliff Report.

- BCv14 App - Changes were made to the Core OData pages.

- BCv14 App - The logic behind the filters on the Sales Cycle Order Cues was reviewed.

- BCv14 App - Changes were made to the Inventory Cockpit Setup.

- BCv14 App - Changes were made to the Sales Cockpit Setup.

- BCv14 App - A Manager Activity panel to view all salespersons cues was added to the Sales Cockpit.

- BCv14 App - Changes were made to the Inventory Alerts Cliff Report.

- BCv14 App - The Sales Cycle Pages were published as OData pages. 

- BCv14 App - A Role Centre was created for the Inventory Cockpit. 

- BCv14 App - A Role Centre was created for the Sales Cockpit. 

- BCv14 App - details from the Sales Cycle when the order is invoiced. The order history should be kept.

- BCv14 App - Amended the Customer Alerts on the Alerts Cliff Page so that they now toggle to expand. 

- BCv14 App - The Usage Category property was added to the Power BI objects. 

- BCv14 App - Changes were made to the Activity Panel. An Action was added to access the Setup Card and the About Action was surfaced on the Activity Panel.

- BCv14 App - Changes were made to the Sales Alerts Cliff Report.

- BCv14 App - New OData Pages for Salesperson/Purchasers, Item Categories and Location List were created.

- BCv14 App - A setup action was added to the Activity Panels.

- BCv14 App - Activity Panels were added to the standard Sales order Processor Role Centre.

- BCv14 App - A Publish Web Service page was created.

- BCv14 App - New standard OData pages were created for the build.

- BCv14 App - A Sales PBIX build was created.

- BCv14 App - Additional pages were added to the product. 

- BCv14 App - Reviewed the code behind certain Sales Cycle events. 

- BCv14 App - A comment field was added to the customer alert table.

- BCv14 App - Functional and visual changes were made to the Sales Cockpit and to the Cliff Report Activity. Added a send to excel action, and standard NAV reports actions to the ribbon. Displayed values in LCY. Allowed users to expand and collapse per customer on item category values.

- BCv14 App - Cues to display counts and values of quotes and orders issued and won were added to the Sales Cockpit activity page.

- BCv14 App - Changes were made to the Sales Cockpit Setup page removing days as a period, holding the last entry no. on the setup and allowing users to do a full rebuild of the data or to do an incremental refresh..

- BCv14 App - Changes were made to the Sales Cockpit Activity page to limit the sales values displayed to those of the user who is logged on.

- BCv14 App - Changes were made to the Sales Cockpit - Cliff Report turnover page to allow a show all on the customer alert list.

- BCv14 App - Created an Inventory Cockpit.

- BCv14 App - Created a Sales Cockpit.

- BCv14 App - Created functionality to record the Sales Cycle from Sales Quote won, Sales Quote lost to Sales Orders created.

- BCv14 App - Created a page to display dimension data out to Power BI.

- BCv14 App - Created Purchasing pages and queries.

- BCv14 App - Created inventory tables, pages and queries for Power BI.

- BCv14 App - Created Sales Pages and Queries.

- BCv14 App - Created Finance Pages and Queries.

- BCv14 App - Created functionality to include shelf life in the inventory cockpit.

- BCv14 App - The Inventory Cockpit objects were moved into a separate standalone product. 

- BCv14 App - Increased the size of description and name fields from 50 to 100 as per standard D365BC change.

- BCv14 App - Renamed the Power BI Inventory Cockpit objects to begin with SD-BICI.

- BCv14 App - Replaced the old SD Power BI Core objects and added the objects to the SD Power BI Inventory Cockpit build.

- BCv14 App - The Inventory Cockpit objects were moved into a separate standalone product. 

#### Bug Fixes

- BCv14 App - Fixed an issue raised when installing the App.

- BCv14 App - Fixed an error raised when the refresh button was chosen on the Manager Role Centre.

### 2.3.3

#### Enhancements

- For Document Type of Invoice created from a Sales Shipment, stamp the Order No. on the Quote Track List.

- For Document Type of Credit Memo created from a Sales Invoice stamp the Order No. on the Quote Track List.

- Made a change to Report 43006300 so it compiles in NAV 2018 GB.

- Fixed compilation errors for XML Ports 43006300 and 43006301.

- Included Report 43006300 in the release.

- Extended the Sales Quote Tracking functionality to log details and trace a Quote from Quote to Order to Invoice or Credit Memo.

### 2.3.2

#### Enhancements

- SD Utilities - Power BI split into own project.

### 2.3.1

#### Enhancements

- Linkbox: 
- Add a setup field to specify document checkout to a default Drop Point check out path.

### 2.3.0

#### Enhancements

- Launch: 
- Upgrade Launch to use Control Suite. 

Linkbox: 
- Created check in/check out functionality for Linkbox Version Control. 
- Added Edit Permission to Linkbox. 
- Cleaned up code.

#### Bug Fixes

- Linkbox: 
- Fixed Error Message raised when viewing a file in the Drop Point or Versions List. 
- Fixed situation where the View Option was always displaying the same file.

### 2.1.2

#### Enhancements

- Updated readme.txt file. 

- Launch - applied Launch standardised document layouts to the Posted Purchase receipt report 

- Linkbox - enhanced Linkbox file overwrite confirmations.

#### Bug Fixes

- Linkbox - fixed a bug in the scrolling functionality when selecting an Icon for a Drop Point in the Drop Point Card. 
- Linkbox - fixed an issue where when choosing to Edit certain files from the Dropped Files Factbox an error is raised. 
- Linkbox - fixed an issue where Delete Permission on Dropped Files Fact Box not taken into account when you right-click on the Dropped Files Fact Box. 
- Launch - fixed alignment issue on the SD-U Customer Payment Receipt Document.

### 2.1.1

#### Enhancements

- Linkbox - enhanced the Icon Scroller picker. 
- Linkbox - enhanced the Template functionality - allow users to choose to push out the Templates to the Linked tables and select the template they want to attach to the records. 
- Launch - surface filters on SD-U Bank Acc. Recon. Stmt Document. 
- Launch - surface filters on the SD-U Bank Acc. Recon. Stmt Test Document. 
- Launch - improvement in code to allow for barcode record type value. 
- Launch - optimised the image preview generation. 
- Launch - surfaced the newly added Documents to the Role Center. 
- Launch - applied Launch standardised document layouts to the SD-U Customer Payment Receipt Document.

#### Bug Fixes

- Launch - fixed alignment issue on SD-U Sales Return Order Document. 
- Launch - fixed alignment issue on SD-U Purchase Return Order Document. 
- Launch - changed the Launch Documents to use the document currency code rather than customer/vendor currency code when deciding the bank details to use on the footer. 

- Linkbox - fixed a bug in the auto linking functionality of a Template File to a record. 
- Linkbox - fixed a bug in the Version History of Dropped Files Linked to a record. 
- Linkbox - fixed a bug in the Version History of auto-created Template Files. 
- Linkbox - fixed a bug where an error was raised on creation of a new record when a Drop Point (with Versioning turned on) is added to a Card Page. 
- Linkbox - fixed a bug where the Icon Scroller images were not updating. 

- Power BI - fixed an issue where the Return Sales Order as raising an error if there was no BI Setup.

### 2.1.0

#### Enhancements

- Launch: 
- All Launch Documents and Reports underwent a code clean up. 
- A Delivery Docket was added to Launch. 
- A Manifest Report was added to Launch. 
- A Bank Account Reconciliation Statement (Posted Entries) was added to Launch. 
- A Bank Account Reconciliation Statement (UnPosted Entries) was added to Launch. 
- A Stock Take Report was added to Launch.
- A Sales Return Order was added to Launch.
- A Purchase Return Order was added to Launch. 
- A Balance Forward Statement was added to Launch. 
- A standardised layout was applied across all Launch Documents and Reports. 
- All Field Names and abbreviations were standardised. 
- Decimal formatting was standardised across all Launch Documents and Reports. 
- A new Footer totalling layout and a VAT Grid layout was applied and standardised across the Launch Documents. 
- Positioning of Logos was made consistent across all Launch Documents and Reports. 
- A standard Header and Footer layout and banner, for portrait and landscape layouts, was applied across all Launch Documents and Reports. 
- An enhancement was made to allow users to choose the Background and Foreground Header and Footer Banner Colours that would print on all Launch Documents and Reports using a Colour Picker.
- Enhancements were made to the Remittance Advice Reports in Launch. Captions were changed, fields were resized. 
- Functionality to define and display a Barcode on all Launch Documents and Reports was added to Launch. 
- A Report Info Box was applied to the layout of all Launch Documents and Reports.
- Functionality was added to allow users to dynamically add the fields to print in the Report Info Box. 
- Minor layout changes were made to existing individual Launch Documents and Reports.
- New functionality was added to allow users to select the Background and Foreground Header and Footer Banner Colours by using a colourpicker. 
- Improved the resolution of the Report Info Box. 
- Fields and FastTabs for new functionality were added to the Launch Setup Card.

Linkbox: 
- New functionality added to Linkbox to Security Filter Tables and Pages enabling permissions to be set. 
- Updated the Linkbox Setup to include Security Filters 
- New Security Filters for Dropped Files applied. 
- New Security Filters for Drop Areas applied.
- Added Company to membership lookup in Linkbox Security Filters. 
- New Version Control functionality added to Linkbox. 
- Provided Version Edit functionality. 
- When viewing a file in the Drop Area, the file is set to read only. 
- Coded increments for Dropped File Entry No. 
- Created a new Table and Page to list, and provide, Dropped File Version functionality.
- Created Template functionality for Linkbox.
- Changed functionality to retain the SD Linkbox - Orphan Link Files.

Profiler: 
- An XMLPort was created to export and import Profile Select List. 

PowerBI: 
- Added Sales Quote Tracking Functionality to PowerBI. 
- Added functionality to provide for CSV Import/Export for BI Date data. 
- Added the PowerBI Setup Page to the SD Utilities Role Centre.

#### Bug Fixes

- Launch: 
- Fixed bug where the Statement report overwrites any Date Filters that are passed into the report. 
- Fixed bug where colour choices picked using the colour picker were being re-set. 
- Fixed bug where the QR Barcode was not displaying correctly in the Report Information box. 
- Fixed bug in the Launch Report Setup whereby when a new record was added to the Report Info Box Fields for a specific report, the Field No. was not appearing in the order as specified but rather in the order as input. 
- Fix was made to the barcode generation to display as per Launch Report Setup. 
- Minor layout changes were made to existing individual Launch Documents and Reports.
- Fixed bug which allowed a Barcode to be setup on the Launch Report Setup with a DPI of zero. 
- Fixed bug where the List of Reports showing in the Launch Setup was being hard code filtered on an earlier version release. 
- Fixed bug where the InfoBox and Barcode were not being updated.
 
Linkbox: 
- Drop Point Icons on List Pages are intermittently not displaying when the List Page is loaded from within the Role Centre.
- Fixed bug where a link is being created to records with no file attached when a record for a Template File that has no File Imported (a blank Filename field) is created. 
- Fixed error raised when an empty file is dragged and dropped into a Drop Point.

Profiler: 
- Removed irrelevant Actions from the Profile Selection List.

### 1.1.0

#### Enhancements

- Linkbox - created XMLPorts for Upgrade to NAVW19.00 - V2.1.0 
- Profiler - created Profiler Date export 
- Power BI - created BI Date XML Port

#### Bug Fixes

- Launch - fixed bug where statement report overwrites passed in Date Filter.

### 1.0.2

#### Enhancements

- Linkbox - Drop Area was not displaying on the Role Center. 
- Launch - Unable to run statement when specified from report selection.

### 1.0.1

#### Enhancements

- Documentation fixes.

### 1.0.0

#### Enhancements

- Linkbox - Created an XmlPort for setting up control Add-in. 
- Profiler - Refactored the object selection. Rewrote the reports to loop on the questions and do basic formatting of them. 
- Profiler - Renumbered and reordered the Tables and Pages. 
- Cleaned up the objects. 
- Code upgraded to 2016.



