# Excel_Functions/Formulae
<br>
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/34/Microsoft_Office_Excel_%282019%E2%80%93present%29.svg/1200px-Microsoft_Excel_2018_logo.svg.png" alt="Excel Logo" width="100"/>
  <br>
  <h1>Microsoft Excel</h1>
  <p>Microsoft Excel is a spreadsheet program developed by Microsoft.</p>
  <a href="https://www.microsoft.com/en-us/microsoft-365/excel" target="_blank"><strong>Learn more</strong></a>
</div>

<h2>Repo for Excel Functions &amp; Formulae</h2>
<p>Quick cheat sheet for worksheet analysis</p>
<table class="table table-bordered">
  <thead class="thead-light">
    <tr>
<table>
  <tr>
    <th>Functions/Formula</th>
    <th>Syntax</th>
  </tr>
  <tr>
     <td>ADD/SUM</td>
    <td>=SUM(A1:A10)</td>
  </tr>
     <td>Average</td>
    <td>=AVERAGE(C2, C3, C4)</td>
  </tr>
  <td>Average if</td>
  <td>=AVERAGEIF(B2:B5,"<23000")</td>
  </tr>
    <td>Count Filtered Rows</td>
    <td>=SUBTOTAL(3,B2:B10)</td>
  </tr>
    <td>Count Rows</td>
    <td>=ROWS(Array)</td>
  </tr>
    <td>Count</td>
    <td>=COUNT(C1:C4)</td>
  </tr>
    <td>Concatenate</td>
    <td>=CONCATENATE(A2,B2,C2,D2)</td>
  </tr>
    <td>Count Blank</td>
    <td>=COUNTBLANK(A2:B4)</td>
  </tr>
    <td>Count If</td>
    <td>=COUNTIF(A2:A5,"London")</td>
  </tr>
    <td>Date</td>
    <td>=DATE(C2,A2,B2)</td>
   </table>
    
### Syntax in markup version
```r
=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])

=HLOOKUP(lookup_value, table_array, row_index_num, [range_lookup])

=INDEX(return_range, MATCH(lookup_value, lookup_range, [match_type]))

=SUMIF(range, criteria, [sum_range])

=SUMIFS(sum_range, criteria_range1, criteria1, [criteria_range2, criteria2], ...)

=COUNTIF(range, criteria)

=COUNTIFS(criteria_range1, criteria1, [criteria_range2, criteria2], ...)

=AVERAGEIF(range, criteria, [average_range])

=IFERROR(value, value_if_error)

=TEXTJOIN(delimiter, ignore_empty, text1, [text2], ...)

=CONCATENATE(text1, [text2], ...)

=SUBTOTAL(function_num, ref1, [ref2], ...)

=INDIRECT(ref_text, [a1])








