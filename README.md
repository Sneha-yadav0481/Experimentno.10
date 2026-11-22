Program 1: Reading CSV File Using Pandas
Step 1: Start the program.

Step 2: Import the Pandas library.

Step 3: Use pd.read_csv() to read the student dataset from a CSV file.

Step 4: Store the CSV file data in a DataFrame named df.

Step 5: Display the DataFrame.

Step 6: Stop the program.

Program 2: Handling Missing Values in Student Data
Step 1: Start the program.

Step 2: Import the Pandas library and Matplotlib library.

Step 3: Create a dictionary containing student names, marks and study hours.

Step 4: Create a DataFrame using pd.DataFrame(data).

Step 5: Display the original DataFrame.

Step 6: Use fillna() to replace missing marks with the mean of the available marks.

Step 7: Display the updated DataFrame.

Step 8: Stop the program.

Program 3: Grade Calculation Using NumPy
Step 1: Start the program.

Step 2: Import the NumPy library.

Step 3: Use np.where() to check the marks of students.

Step 4: If marks are greater than or equal to 75, assign the grade as "Pass".

Step 5: Otherwise, assign the grade as "Fail".

Step 6: Store the result in a new column named Grade.

Step 7: Display the updated DataFrame.

Step 8: Stop the program.

Program 4: Scatter Plot – Study Hours vs Marks
Step 1: Start the program.

Step 2: Import the Matplotlib library.

Step 3: Use plt.scatter() to create a scatter plot.

Step 4: Pass Study_Hours on the X-axis and Marks on the Y-axis.

Step 5: Set the graph title as "Study Hours vs Marks".

Step 6: Display the scatter plot using plt.show().

Step 7: Stop the program.

Program 5: Bar Chart
Step 1: Start the program.

Step 2: Use plt.bar() to create a bar chart.

Step 3: Pass Study_Hours on the X-axis and Marks on the Y-axis.

Step 4: Set the title as "Bar chart".

Step 5: Display the bar chart using plt.show().

Step 6: Stop the program.

Program 6: Line Plot
Step 1: Start the program.

Step 2: Use plt.plot() to create a line graph.

Step 3: Pass Study_Hours and Marks as X-axis and Y-axis values.

Step 4: Set the marker as *.

Step 5: Set the line style as dashed (--).

Step 6: Set the line width to 3.

Step 7: Set the title as "Line Plot".

Step 8: Display the line plot using plt.show().

Step 9: Stop the program.

Program 7: Marks Comparison Using Bar Chart
Step 1: Start the program.

Step 2: Use plt.bar() to create a bar chart using study hours and marks.

Step 3: Use enumerate() to access each student's marks along with its index.

Step 4: Use plt.text() to display the marks above each bar.

Step 5: Set horizontal alignment to center using ha='center'.

Step 6: Set the chart title as "Marks comparison".

Step 7: Label the X-axis as "Study Hours".

Step 8: Label the Y-axis as "Marks".

Step 9: Set the Y-axis limit from 0 to 100 using plt.ylim().

Step 10: Display horizontal grid lines using plt.grid(axis='y').

Step 11: Display the final bar chart using plt.show().

Step 12: Stop the program.
