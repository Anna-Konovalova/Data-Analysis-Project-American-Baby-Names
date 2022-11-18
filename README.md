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

Data Analysis Summary
------
## 1. Which American names can be considered classic?
&nbsp;
![graph_01](https://user-images.githubusercontent.com/78367070/202752138-ddd6944b-a9a1-4364-a411-e32961fd7ff0.png)
&nbsp;
## 3. What are the top-ranked female names since 1920?
&nbsp;
![graph_03](https://user-images.githubusercontent.com/78367070/202752993-7192f6da-9192-4d7c-9bed-50e0a1390549.png)
&nbsp;
## 5. The rise of the name "Olivia"
&nbsp;
![graph_05](https://user-images.githubusercontent.com/78367070/202753189-e04e8cf1-5b0a-4c2b-9d36-0a78bbaf0086.png)
&nbsp;
## 7. What are the top male names over the years?
&nbsp;
![graph_07](https://user-images.githubusercontent.com/78367070/202753464-dad0bca8-09d0-4420-844a-33d2e97f5e59.png)
&nbsp;
Noah and Liam have ruled the roost in the last few years, but it looks like Michael and Jacob have also spent a good number of years as the top name.
&nbsp;
## 8. Which male names have been the most popular for the longest number of years?
&nbsp;
![graph_08](https://user-images.githubusercontent.com/78367070/202753744-a4a3151e-930f-4278-92cc-9e208500c8ba.png)
&nbsp;
The name Michael has been at the top for more than 40 years - that is over 20 years longer then the next most popular male name, Robert. This result, combined with the graph before that shows most popular male names over the years, indicates that prior to 2000s a popular male name was given to a lot more babies and names also stayed popular for longer. This is compared to the most recent years. This suggests that there is a bigger variety in the chosen names, as well as people's preferences for names change quicker in the recent years.
&nbsp;
## 9. What are the top female names over the years?
&nbsp;
![graph_09](https://user-images.githubusercontent.com/78367070/202754073-fc557709-24e5-4a39-b09a-7eb6605c2fc8.png)
&nbsp;
It can be seen that most recently the names Emily, Emma and Olivia stayed at the top. However, prior to 1970s the name Mary has ruled for a considerable number of years - almost every year between 1920 and 1960, giving place to Linda to several years in 1940s.

This graph mimics the one for male names. There is a bigger variety in the chosen names, as well as people's preferences for names change quicker in the recent years.
&nbsp;
## 10. Which female names have been the most popular for the longest number of years?
&nbsp;
![graph_10](https://user-images.githubusercontent.com/78367070/202754407-cef2a05b-25a8-4f9c-a297-ee4a9023a483.png)
&nbsp;
As noticed above, the name Mary has considerably beaten every other female name by the number of years it has been the most popular.
&nbsp;
