<!-- README.md is generated from README.Rmd. Please edit that file -->
STA 580 / STA 780: R and Introductory Data Mining
=================================================

These are the homework assignments and project guidelines for **R and Introductory Data Mining** at Eastern Kentucky University.

Course Schedule
---------------

<table style="width:289%;">
<colgroup>
<col width="16%" />
<col width="8%" />
<col width="8%" />
<col width="126%" />
<col width="93%" />
<col width="36%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">Date</th>
<th align="left">Week</th>
<th align="left">Unit</th>
<th align="left">Topic</th>
<th align="left">Notes</th>
<th align="left">Reading</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">8/22/2016</td>
<td align="left">1</td>
<td align="left">1</td>
<td align="left">Installing R; R Studio; Pandoc. </br>IDE Orientation</br>Finding Help</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">8/24/2016</td>
<td align="left">1</td>
<td align="left">1</td>
<td align="left">Rmarkdown</br>Rstudio Projects/Reproducibility</br>Finding Help</td>
<td align="left">LAST CLASS BEFORE DROP DATE (28 August)</br>Assign Homework #1</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">8/29/2016</td>
<td align="left">2</td>
<td align="left">2</td>
<td align="left">Binary and unary operators</br>Object classes</br>Interpreted and Compiled languages</td>
<td align="left"></td>
<td align="left">R4DS: 13, 14, 16, 11, 12</td>
</tr>
<tr class="even">
<td align="left">8/31/2016</td>
<td align="left">2</td>
<td align="left">2</td>
<td align="left">Indexing lists, matrices, arrays, and data frames</br>Functional and Literate Programming</td>
<td align="left">Homework #1 Due</br>Assign Homework #2</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">9/5/2016</td>
<td align="left">3</td>
<td align="left">NA</td>
<td align="left"></td>
<td align="left">LABOR DAY - NO CLASS</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">9/7/2016</td>
<td align="left">3</td>
<td align="left">2</td>
<td align="left">Matrix operations</td>
<td align="left">Homework #2 Due</br>Assign Homework #3</br>Assign Midterm Exam #1</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">9/12/2016</td>
<td align="left">4</td>
<td align="left">3</td>
<td align="left">if, for, while, repeat, break part 1</td>
<td align="left"></td>
<td align="left">R4DS: 17.1 - 17.4</td>
</tr>
<tr class="even">
<td align="left">9/14/2016</td>
<td align="left">4</td>
<td align="left">3</td>
<td align="left">if, for, while, repeat, break part 2</br>ifelse</td>
<td align="left">Homework #3 Due</br>Assign Homework #4</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">9/19/2016</td>
<td align="left">5</td>
<td align="left">4</td>
<td align="left">function writing I: constructing functions</td>
<td align="left"></td>
<td align="left">R4DS: 15</td>
</tr>
<tr class="even">
<td align="left">9/21/2016</td>
<td align="left">5</td>
<td align="left">4</td>
<td align="left">function writing II: argument checks</br>Intro to dots.</td>
<td align="left">Homework #4 Due</br>Assign Homework #5</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">9/26/2016</td>
<td align="left">6</td>
<td align="left">4</td>
<td align="left"><code>apply</code> Functions I: apply, lapply, sapply</td>
<td align="left"></td>
<td align="left">R4DS: 17.5 - 17.9</td>
</tr>
<tr class="even">
<td align="left">9/28/2016</td>
<td align="left">6</td>
<td align="left">4</td>
<td align="left"><code>apply</code> Functions II: mapply</td>
<td align="left">Homework #5 Due</br>Assign Homework #6</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">10/3/2016</td>
<td align="left">7</td>
<td align="left">5</td>
<td align="left">Data Management I: Basic transformations</td>
<td align="left"></td>
<td align="left">R4DS: 6, 7, 9, 10</td>
</tr>
<tr class="even">
<td align="left">10/5/2016</td>
<td align="left">7</td>
<td align="left">5</td>
<td align="left">Data Management II: Dates and Strings</td>
<td align="left">Homework #6 Due</br>Assign Homework #7</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">10/10/2016</td>
<td align="left">8</td>
<td align="left">NA</td>
<td align="left"></td>
<td align="left">EXAM WEEK NO CLASS</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">10/12/2016</td>
<td align="left">8</td>
<td align="left">5</td>
<td align="left">Exploratory Data Analysis</br>Graphing</td>
<td align="left">Midterm #1 Due</td>
<td align="left">R4DS: 2-5</td>
</tr>
<tr class="odd">
<td align="left">10/17/2016</td>
<td align="left">9</td>
<td align="left">NA</td>
<td align="left"></td>
<td align="left">FALL BREAK - NO CLASS</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">10/19/2016</td>
<td align="left">9</td>
<td align="left">6</td>
<td align="left">Confidence Intervals</br>Basic Hypothesis Testing (t.test, chisq.test, fisher.test)</td>
<td align="left">Assign Midterm Exam #2</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">10/24/2016</td>
<td align="left">10</td>
<td align="left">6</td>
<td align="left">Linear Regression and ANOVA</br>Model Diagnostics</td>
<td align="left">Homework #7 Due</br>Assign Homework #8</td>
<td align="left">R4DS: 19-23</td>
</tr>
<tr class="even">
<td align="left">10/26/2016</td>
<td align="left">10</td>
<td align="left">6</td>
<td align="left">Linear Regression and ANOVA</br>Model Diagnostics</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">10/31/2016</td>
<td align="left">11</td>
<td align="left">6</td>
<td align="left">Ridge Regression</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">11/2/2016</td>
<td align="left">11</td>
<td align="left">6</td>
<td align="left">Logistic Regression</td>
<td align="left">Homework #8 Due</br>Assign Homework #9</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">11/7/2016</td>
<td align="left">12</td>
<td align="left">6</td>
<td align="left">Survival Analysis (Semi-parametric)</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">11/9/2016</td>
<td align="left">12</td>
<td align="left">6</td>
<td align="left">Survival Analysis (Parametric) (time permitting)</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">11/14/2016</td>
<td align="left">13</td>
<td align="left">6</td>
<td align="left">Information Criteria</br>Likelihood Ratio Tests</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">11/16/2016</td>
<td align="left">13</td>
<td align="left">6</td>
<td align="left">Cross Validation</br>Bootstrapping</td>
<td align="left">Homework #9 Due</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">11/21/2016</td>
<td align="left">14</td>
<td align="left">6</td>
<td align="left">Random Forest (time permitting)</td>
<td align="left">Midterm #2 Due</br>Assign Final Exam</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">11/23/2016</td>
<td align="left">14</td>
<td align="left">NA</td>
<td align="left"></td>
<td align="left">THANKSGIVING BREAK - NO CLASS</td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">11/28/2016</td>
<td align="left">15</td>
<td align="left">7</td>
<td align="left">Random Number Generation</br>Simulation: Sample Size Estimation</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">11/30/2016</td>
<td align="left">15</td>
<td align="left">7</td>
<td align="left">Sample Size Simulation</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">12/5/2016</td>
<td align="left">16</td>
<td align="left">8</td>
<td align="left">Writing Packages (time permitting)</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">12/7/2016</td>
<td align="left">16</td>
<td align="left">8</td>
<td align="left">Writing Packages (time permitting)</td>
<td align="left"></td>
<td align="left"></td>
</tr>
<tr class="odd">
<td align="left">12/12/2016</td>
<td align="left">NA</td>
<td align="left">NA</td>
<td align="left">Help session for final projects</td>
<td align="left">IN CLASS QUIZ</td>
<td align="left"></td>
</tr>
<tr class="even">
<td align="left">12/14/2016</td>
<td align="left">NA</td>
<td align="left">NA</td>
<td align="left"></td>
<td align="left">FINAL EXAM DUE</td>
<td align="left"></td>
</tr>
</tbody>
</table>
