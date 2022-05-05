# School_District_Analysis
`Using Python and the Pandas library to analyze school district data and showcase trends in the schools perfomance.`

## Resources
- Data Source: students_complete.csv & school_complete.csv
- Software:  Software: Python 3.7.7, Anaconda, Jupyter Lab, Git 2.27

## 1. Overview of the School District Analysis:
As we have been analyzing the data set of students_complete.csv for variables such as reading score, math score, passing math percentage, etc, we have now been informed that the school board has detected academic dishonesty in regard to reading and math grades being altered at Thomas High School. This academic dishonesty has occured amongst the 9th grade class, and consequently, the school board requests our analysis to see the full extent of this academic dishonesty. Our first order of business will be to replace the math and reading scores with NaNs, while at the same time keeping the rest of the data intact. Upon doing this, we wil then repeat the analyis of this module and then proceed to write a report that outlines how each change had an influence upon our overall analysis. 

## 2. Results:
- How is the district summary affected?
<img width="1041" alt="How is the district summary affected?" src="https://user-images.githubusercontent.com/95828604/150055104-5c03a3d1-a368-42c3-b4ee-e5e186dd07a8.png">

- How is the school summary affected?
<img width="1189" alt="How is the school summary affected?" src="https://user-images.githubusercontent.com/95828604/150055316-0c2dcafe-8414-46ec-9b31-85261b6b43f6.png">

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Both math and reading scores of all 9th graders that attend Thomas High School were not included as they ended up replaced by NaN. Doing this ensures that the academic dishonesty of the 9th grade does not impact future code. We replaced with NaN, which means not a number, as doing something different, such as inputting a number, would results in changes to the scores across the school in relation to other schools and end up with perfomative issues relative to other schools.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
  <img width="445" alt="Math scores by grade" src="https://user-images.githubusercontent.com/95828604/150056159-f9cd92aa-12c9-4aea-8d5b-c346a3f782c2.png">
  <img width="584" alt="Reading scores by grade" src="https://user-images.githubusercontent.com/95828604/150056318-3668b30b-7796-4c44-b7d1-c063dd002a60.png">
  
  - Scores by school spending
  <img width="1214" alt="Scores by school spending" src="https://user-images.githubusercontent.com/95828604/150056569-8c8ca79f-4834-46c1-bb62-f6de4dd0172b.png">
  
  - Scores by school size
  <img width="1217" alt="Scores by school size" src="https://user-images.githubusercontent.com/95828604/150056904-2844d6f4-195b-4aef-812c-4367b610f012.png">
  <img width="1080" alt="Scores by school size 2" src="https://user-images.githubusercontent.com/95828604/150056924-90d4ef06-9848-4d75-b1bd-639d22c03235.png">
  
  - Scores by school type
  <img width="817" alt="Scores by school type" src="https://user-images.githubusercontent.com/95828604/150057079-079699ef-a9ee-40cd-9186-0a025c1420ba.png">
  
## 3. Summary
After reading and math scores have been replaced, I have come up with four changes to the school district analysis. 
- 1. Math and Reading Scores varied amongst different size schools. In regards to medoum sized schools: Percentage passing with reading droped from 97% to 93%, Percentage passing with math dropped from 94% to 90%, Overall passing percentage also dropped from 91% to 85%.
- This shows that when removing 9th grade student scores, percentage passing in both reading and math decreased. 
- 2. Math and Reading scores obviously had the largest effect upon Thomas High School itself. 
- Thomas High School was removed from the top 5 high schools in the district. 
- The overall passing percentage went from 90.9% to 65.1%.
- 3. Removing 9th grade student scores from Thomas High School resulted in changes across the entire school district. 
- The mean of math scores and reading scores were minimally affected. 
- There was a minimal drop in percentage students passing in both math and reading (1%).
- 4. The removal of the entire 9th grade student scores means that the data was made substantially smaller and the removal means that there is no data to draw upon, when looking at the 9th grade class. Therefore, the analysis of the district is made less comprehensive and its scope becomes a bit more limited. 
