# Excel-Formulas
Sample Data set:
![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/163fd2148752fa24a84cb60fb1f6d709aad1eaa3/form1.png)
=MAX(H2:H10) (Max of start date)
11/8/2003
=MIN(H2:H10) (Min of start date)
12/7/1995
Max salary = max(G2:G10) = 65000
Min salary = min(G2:G10) = 32000
### IF function
If age>30 then "Old" else "Young"
=IF(D2>30,"Old","Young")
### IFS Function
Checks multiple conditions if the conditions are ture, TRUE part will be evaluated else the False part will be executed.
![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/9b4c529fc02175104d85a703b2c855a5df417fb3/form2.png)
### Len Function
Finds the length of the Text string
![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/575816317a2cd2f9e6777db10d5d167a3bef2abf/form3.png)

### Left Function
Extracts the characters from the left part of the string.
![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/595cba91fdf751b8e0fc997ef8dc0998c7297c5d/form4.png)

### Right Function
Extracts the specified number of characters from the right part of the string.
![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/d4e6dada52847cfc5457efe8945f97b9ed3b57bd/form5.png)

One common use of right() is to extract the year from the dates.
![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/f2779bf67ff2ad858585d2da6e56a8aa1e3a8c27/form6.png)
### Text() function
Used to convert the numeric value to Text. It's most commonly used to convert the date format to our likings.


![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/c32b1ad7a2e54a6bfa7870b0e4060f2bcc6bdefd/form7.png)

### Trim() function
Removes unwanted spaces from the text string
![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/4cce4f108550e348cb2c401d812f5e9c09eac21f/form9.png)
### Concat() function
Used to combine two strings
![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/cd2ad0eccb827462f02e03836d211dd2997d44f3/form10.png)

### Substitute() with the number of instances
The instance value is optional. But if you give 1, the first occurrence of old text is replaced by the new one. The remaining will be kept as is. If instance number 2, the second occurrence of that old string is replaced by the new one.
![img alt](https://github.com/nsankareswari-70/Excel-Formulas/blob/e102ece72cb6abf65749a835e94f22005e453623/form11.png)
