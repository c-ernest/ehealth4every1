 STEPS TAKEN TO ACHIEVE THE INDICATOR DASHBOARD

1. Data Quality Task: 
The table was formatted and named "ehealth4every1"
The Year column was added to group the INDICATORS, this also allowed the removal of "2030 and 2040" from the "period" column.
In the State and Period column, the National and 
Jum-19 were cleaned. The National filtered out because it holds different values so cannot be considered and it was deleted while Jum-19 is typographical error and was corrected to Jun-19.
Next 6 duplicates were found when the conditional formatting was used to highlight the duplicates and in removed by Remove Duplicates in the Data Tab.
An Outlier in a distribution is a number that is more than 1.5 times the length of the box away from either the lower or upper quartiles. The standard deviation method was used to solved for the outlier [mean + 2(standard deviation) - upperbound and mean - 2(standard deviation) - lowerbound]. The upperbound(114.4024689) was choosen due to the Value column holds no negative values. 
To detect outlier within states for all indicator across periods, a column of TRUE or FALSE was created to detect the which state to applies to the outlier. The use a formula to determine which cells to format from the new rule in conditional formatting (RED CELL with WHITE FONT)was applied to get the states that falls within the outlier.
After cleaning the dataset, the cleaned dataset was saved as "Data_Cleaned". From this Data_Cleaned, different pivot tables and pivot chart were created namely- Indicator by State, Indicator by Period and Indicator by Percent from Bar_Chart, Line_Chart and Pie_Chart respectively.
Furthermore slicer were inserted into the dashboard and linked through report connections to the three(3) Charts already mentioned above.
Finally the workbook is locked and passworded thn sent to git@github.com:nest2chuks/ehealth4every1.git 
