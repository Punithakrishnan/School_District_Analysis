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
Due to potential academic dishonesty by the ninth grade students of Thomas High School, this analysis was conducted twice. The first trial of this analysis included the full set of student data. In the second trial of this analysis, the ninth grade students of Thomas High School had their scores omitted from the calculations. The entire ninth grade class of Thomas High School have had their scores replaced with NaN. The DataFrame below is a summary representing the District after replacing the ninth graders' scores with NaN. 

<img width="934" alt="Screen Shot 2022-04-02 at 10 49 48 PM" src="https://user-images.githubusercontent.com/98849217/161409123-52c081d3-b9c7-4f62-b8f5-ff5a0b58c47e.png">
Replacing the ninth graders' math and reading scores with NaN resulted in the following changes for Thomas High School:

  The overall passing percentage for Thomas High School fell to 65%
  The overall passing percentage for the entire district fell to 64.9%
  Thomas High School was no longer included on the list of top five schools.
  When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:

  The overall passing percentages of Thomas High School decreased by 0.11%
  The average scores of Thomas High School for math and reading increased by 0.06
  For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
  School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among         their tenth through twelfth graders.
  
  The metrics for Thomas High School 
  <img width="971" alt="Screen Shot 2022-04-02 at 10 56 47 PM" src="https://user-images.githubusercontent.com/98849217/161409283-a914d47c-2e52-4cdf-83bd-ceaae256f86d.png">
  
### School district Summary
  
<img width="1006" alt="Screen Shot 2022-04-02 at 11 01 14 PM" src="https://user-images.githubusercontent.com/98849217/161409501-6f7dfae3-f131-4fc0-bdfc-0b2a660701e7.png">

---

### Top Five Performing School
<img width="993" alt="Screen Shot 2022-04-02 at 11 09 14 PM" src="https://user-images.githubusercontent.com/98849217/161409594-dcd90e07-2a32-4688-9aca-0eee9fc9367e.png">

---

### Last Five Performing school
<img width="994" alt="Screen Shot 2022-04-02 at 11 10 32 PM" src="https://user-images.githubusercontent.com/98849217/161409621-6ab963bb-ce3b-4fdb-891b-fd731531f8eb.png">

---

school summaries and performing schools, the score replacements did affect the ranking of the top five performing schools. Thomas High School ranked second place in the top five performing schools with a 91% overall passing. After replacing both math and reading scores, Thomas High School was taken out of the top five category since they now display a 65% overall passing. On the plus side, these changes did not place Thomas High School among the bottom five performing schools. Those ranks remained the same. Per the revised School Summary, Thomas High School now ranks 8th place among 15 high schools in the district.
<img width="375" alt="Screen Shot 2022-04-02 at 11 12 05 PM" src="https://user-images.githubusercontent.com/98849217/161409653-eb15a7a0-e4c4-4a51-bec0-

---
                                                                  
### Scores by School Spending
                                                               
  <img width="909" alt="Screen Shot 2022-04-02 at 11 13 37 PM" src="https://user-images.githubusercontent.com/98849217/161409680-31b9cb8d-fa19-4413-895b-d53b1cf71602.png">
 
---
### Scores by School Size

<img width="920" alt="Screen Shot 2022-04-02 at 11 15 57 PM" src="https://user-images.githubusercontent.com/98849217/161409744-7110dcf9-40ae-4aac-b9f0-ac41ec7c9a29.png">

---

### Scores by School Type
<img width="741" alt="Screen Shot 2022-04-02 at 11 16 49 PM" src="https://user-images.githubusercontent.com/98849217/161409774-1ba8bc29-18c9-40dd-84df-b5d8442e170a.png">

concluding the last summary on School Types, this data change also affected the passing percentages that compared charter and district schools. Fortunately, it did not affect the average scores for these two school types. Removing the scores resulted in a reduction in charter school's passing percentages. Before the data change, charter schools had very high passing percentages: 94% passing math, 97% passing reading, 90% overall passing. After the data change, charter schools now have a 90% passing math, 93% passing reading, 87% overall passing. On the plus side, these rates are still far superior when compared to district schools.
