## SD BI Inventory Cockpit Releases

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

