# **Absolute Frequency**

Count the absolute frequencies using the following COUNTIF formula:
=COUNTIF(dataset_range,">=“&interval start) -COUNTIF(dataset_range,">“&interval end)  

**Absolute frequency** is a simple count of the number of cases, items, or things. An **absolute frequency distribution** displays those counts, usually in a table.

The set up for an absolute frequency distribution is simple:

1. Create Two Columns.
2. Enter the data you want to track in the left column. For this  example, I’m using the hypothetical example of a manufacturing company  who wants to track accidents within departments.
3. In the right column, enter the count. For this example, it’s the number of departments reporting the stated number of accidents.

| Accidents per year | Number of Cases |
| ------------------ | --------------- |
| 0 – 5              | 12              |
| 6 – 10             | 9               |
| 10 – 15            | 5               |
| 16 +               | 2               |

The above table works well if your data is[ ordinal, interval, or ratio.](https://www.statisticshowto.com/nominal-ordinal-interval-ratio/) The left column is in ascending order, although—depending on what data  you have at hand—you could choose to use descending order instead. 