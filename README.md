<p align="center">
    School District Analysis
</p>

<p align="center">
    Module 4 for Data Science Bootcamp - Python (Jupyter Notebook)
</p>

<p align="center">
    STUDY GROUP FOR MODULE 4 - Ryan Knauff, Cayli Swartz, Marshall Miley, Lora Leonida
</p>

##  **Project Overview**
- The school board needs help with an analysis of data regarding their schools reading and math testing scores. We were provided two seperate csv files. The first contains data regarding the budget, size and type of schools in the district. The second displays data regarding the individual students like their name, gender, grade level, school and reading/math scores.

<p align="center">
     School District data and its purpose
</p>

    1. Why are we analyzing this data?
    2. What is the goal and possible outcomes?
    3. What pieces of data can help build toward and obtain our goal(s)?

- Maria, the Chief Data Scientist for the city school district, is tasked with preparing all standarized test data for analysis, reporting, and presentation to provide insight for performance trends and patterns. The results of this analysis will help the school board create meaningful budgets for these schools. I better create an accurate analysis, while also keeping the utmost confidentiality of this data, as it contains information that is viewed as sensitive.

## **Analysis**
I was able to go through and create a full report by using python to read and write our data into an easy to read report from their csv's. It's important with our analysis to be flexible as of course some new information came to light, and our report needed to adjusted last minute to account for these changes.  It appears the 9th grade students were able to accesss records and altered their reading and math scores. It's important we find these 9th graders from Thomas High School and add NaN to their score so it is not counted in our analysis. This was done using the loc() method after importing the numpy library.

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Deliverable%201.png" width="700"/>
</p>

### **The results...**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Deliverable%201%20-%20Results.png" width="700"/>
</p>








With that being said, Steve is not going to care about our code. Steve is looking for cold hard results that are easy to read and interpret. As I said above, his family's financial future is in my hands.
- When the code is entered, a pop-up instructs the user to choose what year they wish to get results for.
- Enter 2017 and the following results appear:

<p align="center">
  <img src="https://github.com/lawnshogan/stock-analysis/blob/main/VBA_Challenge_2017.png" width="700"/>
</p>

- Run the script again and enter 2018 instead:

<p align="center">
  <img src="https://github.com/lawnshogan/stock-analysis/blob/main/VBA_Challenge_2018.png" width="700"/>
</p>

### **Results**

### 2017:
After the code ran for 0.07 seconds, the results for 2017 showed the following:

1. TERP was the only stock which would have produced a negative return (-7.2%).
2. FSLR had the largest daily volume and was 4th in returns. 
3. DQ, ENPH, FSLR & SEDG all had return gains over 100%.

### 2018:
When running the code for 2018 (0.08 seconds runtime), the results told a different story:

1. All stocks produced a negative return, with the exception of ENPH (81.9%) and RUN (84%).
2. ENPH amd RUN also have the top 2 in total daily volume.
3. DQ, FSLR, JKS, SPWR all had losses of over -35%.

Based on these results, and as an extremely unqualified stock specialist, I might personally want to invest in DQ and SEDG based on the difference in their gains/losses. 
- DQ had almost a 200% return in 2017 compared to a -62.6% in 2018. Lets hope for a better 2019. 
- SEDG exceeded expectations in 2017 and gained 184.5% in returns, compared to a -7.8% loss in 2018.

Hopefully his family does not lose all their money.

### **Summary**

After refactoring the code for this assignment, it made me realize that although it can be tedious, frustrating and time consuming, it is more efficent to refactor code that's already been created than to start from scratch. Someone has already created the code you need (most likely). Your job is to find it and make it work with your project. 

I found myself taking code I found on Google and applying it to my module, however I found it very easy to get confused unless you are only working with one part of the code at a time. I found it was easier taking a larger, complete block of code and edit off that, rather than try and piece together multiple sources of code. 

Another disadvantage I found was how many different ways there are to do one task. Sometimes piecing together code can cause conflict and this defenetly set me back at times. 

Regarding the refactored VBA script, I think it was helpful for the pieces before 1a and after 4. Your sheet is already formatted and ready to go. Copying it over is easy and allows you to direct your attention to the other portions of code we haven't tested, or even created yet.
