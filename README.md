Download Link: https://assignmentchef.com/product/solved-cpts-575-assignment-2
<br>



This assignment has <strong>two exercises. </strong>For questions that ask you to produce a specific plot, include that plot along with the code you used to generate it. You are strongly encouraged to use R Markdown to prepare your solution. Be sure to <u>clearly number each response</u> in line with the questions, and give <u>each plot appropriate axis labels and title</u>.

<ol>

 <li>This exercise relates to the College data set, which can be found in the file College.csv on the course’s public webpage (https://scads.eecs.wsu.edu/index.php/datasets/). The dataset contains a number of variables for 777 different universities and colleges in the US. The variables are</li>

</ol>

<ul>

 <li>Private : Public/private indicator</li>

 <li>Apps : Number of applications received</li>

 <li>Accept : Number of applicants accepted</li>

 <li>Enroll : Number of new students enrolled</li>

 <li>Top10perc : New students from top 10% of high school class</li>

 <li>Top25perc : New students from top 25% of high school class</li>

 <li>Undergrad : Number of full-time undergraduates</li>

 <li>Undergrad : Number of part-time undergraduates</li>

 <li>Outstate : Out-of-state tuition</li>

 <li>Board : Room and board costs</li>

 <li>Books : Estimated book costs</li>

 <li>Personal : Estimated personal spending</li>

 <li>PhD : Percent of faculty with Ph.D.’s</li>

 <li>Terminal : Percent of faculty with terminal degree</li>

 <li>F.Ratio : Student/faculty ratio</li>

 <li>alumni : Percent of alumni who donate</li>

 <li>Expend : Instructional expenditure per student</li>

 <li>Rate : Graduation rate</li>

</ul>

Before reading the data into R or Python, you can view it in Excel or a text editor. For each of the following questions, include the <u>code you used to complete the task</u> as your response, along with <u>any plots or numeric outputs produced</u>. You may omit outputs that are not relevant (such as dataframe contents), but still include all of your code.

<ul>

 <li>Use the csv() function to read the data into R, or the csv library to read in the data with python. In R you will load the data into a dataframe. In python you may store it as a list of lists or use the pandas dataframe. Call the loaded data college. Ensure that your column headers are not treated as a row of data.</li>

 <li>Find the median cost of books for all schools in this dataset.</li>

 <li>Produce a scatterplot that shows a relationship between two features of your choice in the dataset. Ensure it has appropriate axis labels and a title.</li>

 <li>Produce a histogram showing the overall enrollment numbers (Undergrad plus F.Undergrad) for both public and private (Private) schools. Ensure it has appropriate axis labels and a title.</li>

 <li>Create a new qualitative variable, called Top, by binning the Top25perc variable into two categories. Specifically, divide the schools into two groups based on whether or not the proportion of students coming from the top 25% of their high school classes exceeds 50%.</li>

</ul>

Now produce side-by-side boxplots of acceptance rate (based on Accept and Apps) with respect to the two Top categories (Yes and No). <u>How many top universities are there?</u>

<ul>

 <li>Continue exploring the data, producing <u>two or more new plots of any type</u>, and provide a <u>brief summary of your hypotheses and what you discover</u>. You may use additional plots or numerical descriptors as needed. Feel free to think outside the box on this one but if you want something to point you in the right direction, look at the summary statistics for various features, and think about what they tell you. Perhaps try plotting various features from the dataset against each other and see if any patterns emerge.</li>

</ul>

<ol start="2">

 <li>This exercise involves the Auto.csv data set found on the course website. Make sure that the missing values have been removed from the data.</li>

</ol>

<ul>

 <li>Specify which of the predictors are quantitative, and which are qualitative? Keep in mind that a qualitative variable may be represented as a quantitative type in the dataset, or the reverse. You may wish to adjust the types of your variables based on your findings.</li>

 <li>What is the range, mean and standard deviation of each quantitative predictor?</li>

 <li>Now <u>remove the 45th through 85th (inclusive) observations</u> from the dataset. What is the <u>range, mean, and standard deviation</u> of each predictor in the subset of the data that remains?</li>

 <li>Using the full data set, investigate the predictors graphically, using scatterplots, correlation scores or other tools of your choice. Create some <u>plots highlighting the relationships</u> <u>you find</u> among the predictors. <u>Explain briefly</u> what the relationships between variables are, and what they mean.</li>

 <li>Suppose that we wish to predict gas mileage (mpg) on the basis of the other variables. Which, if any, of the other variables might be <u>useful in predicting </u><u>mpg</u>? <u>Justify your answer.</u></li>

</ul>


