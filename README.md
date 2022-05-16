# School_District_Analysis
## Overview of School Distrct Analysis
The school district's board asked for an analysis of math and reading scores at the high schools of the district. Using Pandas, an analysis was completed that broke down math and reading scores by school type (charter or public), by grade (9th - 12th), school size, and spending per student. After reviewing the analaysis, the school district became suspicious that the scores at Thomas High School for 9th graders may have been altered. The analysis was completed again however in the second analysis, the scores for Thomas High School were replaced with NaNs and the rest of the data remained intact. A review was completed of the revised data.
## Results
- How is the District Summary Affected?
  - There were numerically negibile differences in overall district scores as seen below (the revised scores are in the top figure). The largest change is     0.3% decrease in the percentage of students passing overall. 
![Screen Shot 2022-05-15 at 8 41 02 PM](https://user-images.githubusercontent.com/67160240/168504180-47071a77-2032-4b6c-8c27-086f93760e57.png)
![Screen Shot 2022-05-15 at 8 43 22 PM](https://user-images.githubusercontent.com/67160240/168504186-0664b63b-1b84-4be5-9b3f-a57ef073d920.png)
- How is the School Sumaary Affected?
  - The overall results for Thomas High School had very small differenes in the revised analysis. 
![Screen Shot 2022-05-15 at 8 51 46 PM](https://user-images.githubusercontent.com/67160240/168504365-8bb80e7d-da44-4fe8-b796-2d92dce72a6e.png)
![Screen Shot 2022-05-15 at 8 52 27 PM](https://user-images.githubusercontent.com/67160240/168504371-74ed39df-3418-4671-9379-885895e56b82.png)
- Effect of Replacing the 9th graders' Math and Reading scores
  - Since the scores did not change significantly when the 9th graders' scores were removed, the performance of Thomas High School compared to the rest of     the district did not change. However, if you take a look at the school and take the 9th graders scores into account, the passing math, passing reading,     and overall passing scores drop drastically with all scores under 70%.
![Screen Shot 2022-05-15 at 9 01 45 PM](https://user-images.githubusercontent.com/67160240/168504384-d1c1aade-6dc0-47b7-a24b-76199d868031.png)
![Screen Shot 2022-05-15 at 8 59 01 PM](https://user-images.githubusercontent.com/67160240/168504390-ca04e16c-9c50-4eff-85fb-d3417f16b7a9.png)
- How does replacing the ninth-grade scores affect math and reading scores?
  - There is no effect on the other grades as only 9th grades scores were removed. The other grades' scores stayed intact.
- How does replacing the ninth-grade scores affect scores by spending size?
  - There is a minimal effect (< 1%) on scores by spending size.
- How does replacing the ninth-grade scores affect scores by school size?
  - There is a minimal effect (< 1%) on scores by spending size.
- How does replacing the ninth-grade scores affect scores by school type?
  - There is a minimal effect (< 1%) scores by school type.
## Summary
After the analysis was completed by replacing the 9th grader scores with NaNs, the biggest changes were seen in Thomas High School's overall passing score (90.4% vs. 60.7%), math passing score (93.3% vs. 63.9%), and reading passing scores (97.3% vs. 69.7%). There was also small changes (<1%) in the overall district scores.
