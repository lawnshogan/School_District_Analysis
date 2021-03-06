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
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%201.png" width="700"/>
</p>

### **The results...**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%201%20-%20Results.png" width="700"/>
</p>


With this data now accounted for in our dataset, it's time to move onto the second deliverable and recalulate the following metrics:

- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type

### **The District Summary**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20District%20Summary.png" width="700"/>
</p>

### **The School Summary**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20School%20Summary.png" width="700"/>
</p>


### **Top 5 / Bottom 5 Schools**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20Top%20and%20Bottom%20Schools.png" width="700"/>
</p>

### **Average Math / Reading Scores per Grade Level**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20New%20Math%20Scores.png" width="700"/>
</p>

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20New%20Reading%20Scores.png" width="700"/>
</p>


### **School Spending per Student by School Size**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20Average%20school%20spending%20by%20size.png" width="700"/>
</p>

### **School Spending per Student by School Type**

<p align="center">
  <img src="https://github.com/lawnshogan/School_District_Analysis/blob/main/Readme_Images/Deliverable%202%20-%20Average%20school%20spending%20by%20type.png" width="700"/>
</p>


### **Results**


1. How is the district summary affected?
- The overall passing percentages lowered slightly because the fake, high scores were taken out of consideration to the overall total.
2. How is the school summary affected?
- The overall passing percentages lowered slightly for Thomas High School - high scores were taken out of consideration to the overall total.

3. How does replacing the ninth graders??? math and reading scores affect Thomas High School???s performance relative to the other schools?
- The sample size of Thomas High School becomes smaller and will affect the overall performance numbers. We can assume they created higher grades for these students, therefore taking them out will lower the overall scores of the school.

4. How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade - The overall grade scores lowered slightly.
- Scores by school spending - The students were still counted however we did not consider their score. The overall school spending did not change.
- Scores by school size - This score was also affected because the school size was altered.
- Scores by school type - The numbers reflected change because the school type containing Thomas High School will have a lower score with those 9th graders not included.




### **Summary**

This analysis was interesting but I also thought the results were somewhat predictable, which can happen in data science. When students try to cheat and change their scores, they are not giving themselves F grades - They are probably giving themselves A and B grades. 

With this in mind, when we alter our data by taking out the 9th graders for a particular school, your overall passing scores will lower, because you are getting rid of the results of higher scores.

The budget per district and per school size will be altered as well as the new data is accounted for and calculated.
