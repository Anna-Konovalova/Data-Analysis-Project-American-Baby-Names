Data Analysis Project
======
American Baby Names
======
Project Overview
------
How have American baby name tastes changed since 1920? Which names have remained popular for over 100 years, and how do those names compare to more recent top baby names? In this project I have answered these questions and more. More specifically, I have addressed the following:
1. Which American names can be considered classic?
2. Was each name classic and popular across many years or trendy, only popular for a few years?
3. What are the top-ranked female names since 1920?
4. A scenario in which a friend is picking a name based on certain criteria.
5. The rise of the name "Olivia".
6. A trend where many male babies are given the same name.
7. What are the top male names over the years?
8. Which male names have been the most popular for the longest number of years?
9. What are the top female names over the years?
10. Which female names have been the most popular for the longest number of years?

Tech
------
I have performed data manipulation and querying locally on my computer using SQL. Then I have used Python Pandas in order to read my queries in Jupyter Notebook. For data visualisation I used Python's Matplotlib and Seaborn libraries. 

Data
------
The data is provided by the United States Social Security Administration, which lists first names along with the number and sex of babies they were given to in each year. For processing speed purposes, the dataset is limited to first names which were given to over 5,000 American babies in a given year. The data spans 101 years, from 1920 through 2020.
<h3 id="baby_names"><code>baby_names</code></h3>
<table>
<thead>
<tr>
<th style="text-align:left;">column</th>
<th>type</th>
<th>meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;"><code>year</code></td>
<td>int</td>
<td>year</td>
</tr>
<tr>
<td style="text-align:left;"><code>first_name</code></td>
<td>varchar</td>
<td>first name</td>
</tr>
<tr>
<td style="text-align:left;"><code>sex</code></td>
<td>varchar</td>
<td><code>sex</code> of babies given <code>first_name</code></td>
</tr>
<tr>
<td style="text-align:left;"><code>num</code></td>
<td>int</td>
<td>number of babies of <code>sex</code> given <code>first_name</code> in that <code>year</code></td>
</tr>
</tbody>
</table>
