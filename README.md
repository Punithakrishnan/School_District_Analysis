# School_District_Analysis
### Performing an analysis using school and student data to inform a school district on their budget and priorities.
---
The purpose of this project is to analyze the data of an entire School District, such as funding and student grades, to learn new insights and visually provide clear results on each school's performance. Additionally, to uphold state-testing standards, this analysis was conduced twice due to potential academic dishonesty among a group of students. The implications of omitting the potentially dishonest data are also discussed.
---
## Resources
---
Resources: All data used in this analysis is found inside of the Resources folder.
Software: Python 3.7, Anaconda, Jupyter Notebook
## Result
The first step of this analysis was to take out the dishonest grades from the ninth graders test scores from Thomas High School, this was done by cleaning the code. The code used is below:

student_data_df.loc[(student_data_df["grade"]=="9th") & (student_data_df["school_name"]=="Thomas High School") , "reading_score"] = np.nan

student_data_df.loc[(student_data_df["grade"]=="9th") & (student_data_df["school_name"]=="Thomas High School") , "math_score"] = np.nan

school_data_complete_df = pd.merge(student_data_df, school_data_df, how="left", on=["school_name", "school_name"])

school_data_complete_df.head()
