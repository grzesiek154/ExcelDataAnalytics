# Descriptive Statistics Tabular, Graphical and Numerical summaries of data.

## Tabular and Graphical Displays For Categorical Variables Single Variable:

### Frequency Distribution:

Is a tabular summary which:

- Lists all the unique values or ranges of values in a set of data, called categories or classes
- Categories must be Collectively Exhaustive Categories (enough categories so nothing is left out) and Mutually Exclusive Categories (no item can fit into more than one category)
- Shows the number of observations (count or frequency) in each of the categories or classes
-  Goal is to is to provide information about frequencies (count)

### Relative Frequency Distribution:

- Shows decimal value that represents "parts compared to the whole" (used in chapter 4 for assigning probabilities)

### Column/Bar/Pie charts:

- Used to show Frequency Distribution or Relative/Percent Frequency Distribution for Categorical Data
- Counts across categories. Height of columns convey(oddawać, wyrażać, przekazywać) count. Order of categories conveys no info
- There are "gaps" between columns to indicate that the data is categorical or a discrete quantitative variable (not a continuous quantitative variable). Columns do not touch

### Pie Chart:

- Used to show Percent Frequency Distribution
- Research shows that Column or Bar Charts may be more effective than Pie Charts

### Pareto Chart:

- Column Chart that is sorted Biggest to Smallest
- Quality Control Pareto Chart (Column Chart Sorted Descending Left To Right) and then add a Cumulative Percentage Line data series to chart







## Tabular and Graphical Displays For Quantitative Variables Single Variable:

### Frequency Distribution:

- Lists all the unique values or ranges of values in a set of data, called categories or classes
- Categories must be Collectively Exhaustive Categories (enough categories so nothing is left out) and Mutually Exclusive Categories (no one item can fit into 2 or more categories)

- Shows the number of observations (count or frequency) in each of the categories or classes
-  Goal is to is to provide information about frequencies (count)

### Creating Classes for Quantitative Variables:

- The goal is to reveal the natural distribution or shape or variation of the data. This is the "art side of statistics". It takes practice to get the hang of it
- Determine the number of nonoverlapping classes. Goal is to have enough to show natural shape of data. One general guideline is: 2^k > n, where n = count and k = number of classes
- Determine the width of each class with something like: approx. width = (Max-Min)/(Number of classes). Trial and error is usually required
- Determine the class limits: the key is to not create classes where you can would double count. Trial and error is usually required
- If you have a discrete variable (or a continuous variable that is shown as a whole number) it is just a matter of getting the lower and upper limit, like: 0-9, 10-19...
- If you have a continuous Variable and you choose to use the upper limit from the previous class as the lower limit for the current class, be sure to include the equal sign on either the lower or upper, but not both. Create classes like: 0 <= Sales < 20, 20 <= Sales <40... or 0 up to 20, 20 up to 40...
- When we create a set of classes, we are creating a type of category for our continuous quantitative variable
- Making the classes all the same width helps to create tables and charts that are more easily interpreted
- Sometimes if there are a few large values or small values, it may be efficient to create an open ended class
- Class midpoint is calculated as the halfway mark between the lower and upper limit

### Relative Frequency Distribution:

- Shows decimal value that represents "parts compared to the whole" (used in chapter 4 for assigning probabilities)

### Percent Frequency Distribution:

- Formats Relative Frequencies with Percent Number Format

### Histograms

- Used to show frequency distribution of continuous quantitative data over a set of class intervals (lower and upper limit for each category)
- Column or Bar Charts where columns are touching to indicate that the variable is continuous
- Columns touch to indicate that no numbers can fit between classes. "No numbers can fit between columns - no gaps"
- Height of columns convey count
- Order of classes is important to help reveal shape of data, or distribution of data

### Skew of Histograms

What does the distribution of Histogram Columns look like?

- Skew Left or Negative means a few short Histogram Columns are on the low end (pull mean down)
- Skew Right or Positive means a few short Histogram Columns are on the high end (pull mean up)
- No Skew means the distribution is bell shaped or nearly bell shaped

### Cumulative Percent Frequency Distribution is a tabular summary which:

- Shows the cumulative number of observations (count or frequency) in each of the categories or classes. Count for "less than or equal to" upper limit of class. The last class will be equal to the count of all items in the data set

### Cumulative Percent Frequency Distribution is a tabular summary which:

- Shows the percent cumulative frequency in each of the categories or classes. Calculation is based on Running Total divided by count of all items in the data set. The last class will be equal to 100%
- With any particular class you can say something like: "xx% of the occurrences are less than or equal to the upper limit of the class"

### Cumulative Percent Frequency (Ogive) Charts. Not in textbook

- Use an X-Y Scatter Chart to plot the set of x-y values, where x is equal to the upper limit of the class and y is the Cumulative Percent Frequency; or use a Histogram with Frequencies and add a second set of data points that represent the Cumulative Percent 

### Dot Plot

- Summarizes data by the number of dots above each category on the horizontal axis
- Used to show distribution of quantitative data over entire range of data
- Dot Plots are good for comparing two or more data sets

### Steam and Leaf

### Allows you to see the shape of the distribution for a quantitative variable without losing the identity of each value





## Tabular and Graphical Displays For Two Variables

### Crosstabulation

- PivotTables are perfect for creating Crosstabulations, including the ability to show percentages with by right-clicking the Values area and point to "Show Values as" and then choose "% of Grand Total", "% of Row Total", "% of Column Total"
- Counting with two criteria or conditions
- Allows you to compare two variables and shows relationship between two variables (can be categorical or quantitative)
- One variable is a Row Header and the other is a Column Header
- Grand Totals show Frequency Distributions for Row and Column Criteria, but is not the main idea of a Cross Tab

### Clustered Column (Excel Name) = "Side-By-Side Bar" in textbook

- Good for displaying crosstabulation. Emphasis is on comparing the categories listed in the legend

### Stacked Column (Excel Name) = not in textbook

- Good for displaying crosstabulation. Emphasis is on comparing the categories listed in the horizontal axis

### 100% Stacked Column (Excel Name) = "Stacked Bar" in textbook

- ### **Good for displaying crosstabulation. Similar to a pie chart where each column is 100%. Emphasis is on comparing percentages for categories in Legend**

### Simpson's Paradox

- Conclusion from an aggregate of two or more crosstabulations may be the reverse of the individual crosstabulations because of a hidden variable

### Scatter Chart for X-Y Data

- Goal: see if there is a relationship between two categorical variables
- Horizontal Axis = Independent Variable = x. Vertical Axis = Dependent Variable = f(x) = y
- Two Numbers plotted, one on each axis.
  To plot point: 1) Move along x axis, then 2) move along y axis, record point
- In Excel, X values should be to left of y values, and field (variable names at top of each column).
- Use X-Y Scatter Plot Chart, not Line Chart

# Exel Tips

## Advanced Filter, Extract Unique List

Advanced Filter dialog Box:

- Action: Copy to another location
- List: Proper Data Set. Can be all fields, or just some of the fields.
- Criteria: we will leave this empty for our "Extract Unique List"
- Copy to: Top left cell of Extract Range
- Unique records only: Used to extract a unique list. Can be uses on a single column or multiple columns.
- Be sure to have field name in data set; if you do not you will get 1 duplicate because it will always treat the first row as a field
- When you run Advanced Filter (AF), 2 Defined Names are created: Extract & Criteria. This is so AF can remember for next time



## Pivot table vs Formulas

- Formulas update automatically when the raw data changes. There are more options with formulas, like more functions and more grouping options for upper and lower limits when creating classes. With formulas you can choose which columns in your tabular summary that you would like in your chart; whereas, with a PivotTable, you cannot choose because all columns will show up in the chart and cannot be edited out
- PivotTables update after raw data changes only after you refresh. Right-click PivotTable and point to Refresh. When you make a PivotTable tabular summary, all columns will show up in the chart and cannot be edited out



## Pivot Table and show value as

- After you drag a Field from the PivotTable Field List to the Values area, you can right-click the Values area in the PivotTable and point to Show Values As. This will allow us to change the calculation to calculations like: % of Column Total, % of Row Total,  % of Grand Total, Running Total and % of Running Total. We will use this feature throughout the class

## PivotTables Grouping for Quantitative Variable (Number)

- Drag Number Field to Row area, right-click in Row area, point to "Group", Look at "Starting at" (Min) and "Ending at" (Max), then set the increment or class width for class (category) where it says "By". Note [1]: For Decimal Values, the grouping feature creates class labels like 0-10, 10-20, 20-30, etc. where the Upper Limit is not included in the class (category) and the Lower Limit is included. A 10 value will be counted in the class 10-20, not 0-10. Be sure to include enough classes so that the category or class labels are not ambiguous. For example, in the video example for grades, the last class was 90-100 and the 90 value and the 100 value were both included in the count and so the class label was ambiguous: we resolved this ambiguity by change the "Ending at" (Max) value from 100 to 110. Note [2]: For Integer Values, the grouping feature will create non-ambiguous class labels like 16-22, 23-29, 30-36, etc.

## Power Query

- If you have multiple Text Files in a Folder, using Power Query (a COM add-in for Excel), you can use the Import From File, Import From Folder option to quickly import many files at one time. When the Data gets dumped into the Query Editor window, Right-Click the "Content" Field and point to Remove Other Columns. After the "Content" Field is the only field, click the double downward-pointing button to expand the columns to see all the fields. Then use the Filter Drop Down to Filter out the Field Names from the data set. If you don't see the Field name in the Filter dropdown, click the "List may be incomplete - Load More" link. Then you can name the Query and click the Close and Load to button, then the Close and Load To button a second time, then select your location in the Excel Workbook to place your table of data.

## VLOOKUP Function

- Exact Match: means VLOOKUP starts at first item in first column & looks at each item in column until it finds an exact match
  If there are duplicates, it only finds the first one
  If it can't find a match, it returns an #N/A error
  1st column is where VLOOKUP "looks" to figure out what row in the table has the value it wants
  Tell VLOOKUP what value it should look up = 1st argument
  Tell VLOOKUP where the table is = 2nd argument
  Tell VLOOKUP what column holds the value you want to return to the cell = 3rd argument
  Tell VLOOKUP whether you are doing exact ( 0 ) or approximate (leave argument blank) match = 4th argument