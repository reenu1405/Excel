<h1> Excel_project_Bike_Buyers</h1>

[Path of the DataSet](https://github.com/reenu1405/Excel/blob/main/Excel%20Project%20Dataset%20alex.xlsx "Excel_project_Bike_Buyers")
**: Excel Project Dataset alex.xlsx = It is Raw Dataset we gonna work on this.**

*Steps:*	
*   [Data Overview](#DataOverview)
*   [Delete Duplicate](#DeleteDuplicate)
*   [Clean The Data](#clean)
*   [Pivot Table](#pivot)


<h2 id="DataOverview">Data Overview</h2>
        Go through the Dataset. Select the Dataset press Select all button (above left corner) <br/>
        Add the :white_check_mark: Filter to all headers from Data -> Sort & Filter -> Filter or <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + L  <br/>
        Check all the spelling from filter dropdown if you see any mistake correct it from  -> Review -> Spelling <br/>

<h2 id="DeleteDuplicate">Delete Duplicate</h2>
        Select the Dataset (<kbd>Ctrl</kbd>+A) or simply press Select all button -> Data -> Data Tools -> Remove Duplicates -> :white_check_mark: Select all the columns and :white_check_mark: *My table has headers*.
<h2 id="clean">Clean The Data</h2>

*   **Marital Status:**  Correct the similar abb. such as M = Married and M = Male in Marital status and Gender respectively. <br/> -> <kbd>Ctrl</kbd>+H -> click on options to maximize the find and replace box -> in :arrow_down_small: Search dropdown select: by Column -> :white_check_mark: Match Case -> select the column Marital Status -> Replace M with Married and S with Single  <br/>
*   **Gender Column:** Do the same with Gender column : M to Male and F to Female.
*   **Income :**   Select the column -> Go to Home -> Number -> :arrow_down_small: Select currency -> then Decrease the decimal option(remove the decimals).
*   **Age Brackets:**  Insert a column before purchased bike ->select purchased bike column -> right click -> Insert -> in M2 use nested if : =IF(L2>54,"Old", IF(L2>=31,"Middle Age",IF(L2<31,"Adolescent","Invalid"))).

<h2 id="pivot">Pivot Table</h2>
Create a new sheet : select any cell -> Insert -> Pivot -> give the range of whole table in Working Sheet-> OK.

Ques: Build a Dashboard : The average income of person who either bought or did not buy a bike.
Income -> Value
Gender -> Rows







