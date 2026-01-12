# Londonderry, NH

Welcome! This repository contains files and artifacts related to my role on the Londonderry [Budget Committee](https://londonderrynh.gov/324/Budget-Committee). This page and repository will be updated through the FY27 and following budget cycles.

## FY27 Town Budget

The FY27 budget season is currently in progress. Departments have made budget presentations and requests, and these proposals are being reviewed leading up to the Deliberative Session and Election.

### Budget Analysis

Please see the file [Town of Londonderry FY27 Budget Analysis.2026-01-05.xlsm](https://github.com/plzm/londonderry/raw/refs/heads/main/town/Town%20of%20Londonderry%20FY27%20Budget%20Analysis.2026-01-05.xlsm) in the **town** folder.

==========

&rarr; **IMPORTANT NOTE WHICH YOU SHOULD REALLY READ**:

_Other than the town-provided raw data which I imported into this file, all tabs, formulas, macro code, and other changes and additions to this file were created by me._

_The Town of Londonderry does NOT endorse or take any responsibility for this file, or anything in this repository. Before you base any decisions or statements on anything you find here, you should double-check all data, formulas, and calculations._

_I recommend that if you want to use this data in any public setting, you first contact either me or the Town Finance Department to verify the accuracy of this data and statement(s) based on it._

==========

This is a macro-enabled Microsoft Excel file. You can download and open it on your computer. You will be prompted that macro functionality has been disable. You do NOT need to enable this functionality in order to use this spreadsheet. The macro functionality is only used when importing raw data provided by the Town Finance Department.

![Excel warning that Macros have been disabled](images/excel-macro-disabled.png "excel-macro-disabled.png")

**File Contents**

- A set of tabs with per-department budget proposals. These are named "nn - Department Name - FY 2027" where "nn" is the department number. This data was provided by the Town Finance Department in raw form, and imported into this file using the above-referenced macros which I wrote for this purpose.
- A "CPI" tab. This contains Consumer Price Index data from the U.S. Bureau of Labor Statistics. The tab includes source links and screenshots for this data.
- A "Discretionaries" tab. This is a list of all the accounts I found in the town source data. I added a "Discretionary" column, and labeled each account as discretionary or not (TRUE/FALSE). I used my judgment for which accounts are not discretionary (e.g., salaries, benefits, debt service, etc.) and which are (e.g., office supplies, travel, training, etc.). The discretionary flag is used in my analysis of which departments and lines exceed either the four-year town budget change trend or the four-year CPI trend; only discretionary accounts are considered in that analysis.
- A "Consolidated Lines" tab. This is created by the macros I wrote. It consolidates all department budget line items onto a single tab, harmonizes the layout so that every budget line item is complete, and removes the visual hierarchies and subtotals used in the source data. The intent here was to bring all the data together to enable cross-departmental and cross-period (fiscal years) analysis by amount and percent.
- Two "Pivot" tabs. One is "Pivot by Dept.", with an account sub-level. The other is "Pivot by Acct.", with a department sub-level. These pivot tables are created from the "Consolidated Lines" tab, and allow for dynamic exploration of the data. In particular, rapid sorting and prioritization of budget lines for consideration of potential adjustments (reductions) is provided here.
-A "Change Log" tab. This lists the exact changes I made to the source data provided by the Town Finance Department. These changes are primarily to allow for correct consolidation across departments and accounts. Changes include removing duplicate columns and making account names and account numbers consistent when they were clearly the same but spelled slightly differently. (This throws off aggregates.)

![Some of the tabs in the town Excel budget analysis file](images/town-excel-tabs.png "town-excel-tabs")

