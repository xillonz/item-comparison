# Item Comparison


## Description

A quickly built example of using Google Sheets as a database for a static page.

The otherwise static page displays a searchable and filterable table based of a Google Sheets sheet. Intially built to help compare similar products.

Uses V3 of the Google Sheets API


## Implementation

Column headers within the sheet are used as the table headers within the page. 
Column headers can be appended with suffixes to add different filters within the resulting comparison page.
Available filters are:

 * range
 * choice
 * search
 
Filters are applied by adding the filter name surrounded by hyphens. `ColumnName-choice-range-`
Multiple filters can be applied to each column.
Columns can be spread over multiple sheets within the same file, the comparison tool will collate them together and create all relevant filters.


