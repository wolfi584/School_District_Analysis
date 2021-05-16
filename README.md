# School District Analysis

## Overview
There has been notification from the school board that academic dishonesty has occured. There is indication that the 9th graders at Thomas High School have had their math and reading grades changed. At this time the extent of grade alteration is unknown. Despite recently finishing a high quality analysis of the students_complete.csv file, the school board has requested I change my analysis to exclude all 9th grade reading and math scores from Thomas High School. The prupose of this is to avoid presenting skewed results caused by false data. Replacing all of these scores with Nan's will lead me to provide data that is presenting a more truthful representation of the school district's actual performance. Once completing the second analysis, I will compare and contrast the two analysises of the students_complete.csv file.

## Results
  * **How is the district summary:** The overall passing percentage changed from 90.6% to 65.1% for THS. 
  * **How is the school summary affected:** After the 9th grade math and reading scores were replaced by Nan's, the overall passing percentage decreased from 90.0% to 65.1%. 
  The average math and reading scores didn't change much and stayed at 83.4% and 83.9%, respectivley. However, there was a large drop in passing math and passing reading scores.     The passing math score changed from 93.3% to 66.9%, and the passing reading score decreased from 90.9% to 69.7%.
  * **Impact in school ranking:** Regarding overall passing percentage, Thomas High School went from being ranked one of the top 5 high schools to being ranked 8th out of 15 schools.

* **Other effects of changing THS 9th grade scores:**
  * **Math and reading scores by grade:** Other than the replaced math and science scores for THS students, all other math and science scores from other schools remain the same. However, if averages or other statistical information were to be performed the outcomes would change. 
   * **Scores by school spending:** The lower a school scores in math and science, there is a general trend of receiving more funding. There are of course, other factors affecting spending, including school size and school type. Removing the 9th grade scores from THS places them lower in school rankings; potentially changing the amount of funding they receive per student.
  * **Scores by school size:** Research reveals that smaller and medium schools typically score higher than larger schools. For example, small size schools (< 1000) have an average math score of 83.8% and large schools (2000-5000) have an average math score of 77.7%. 
  * **Scores by school type:** In average math and science scores and passing percentages, charter schools scored higher than district schools. THS is a charter school. Even though their school ranking summary signifigantly dropped after including two Nan scores, they are still in the top 53% of schools within the district.

## Images

![A](https://github.com/wolfi584/School_District_Analysis/blob/main/Resources/THS%20school%20stats.PNG?raw=true)
![B](https://github.com/wolfi584/School_District_Analysis/blob/main/Resources/district%20vs.%20charter%20schools.PNG?raw=true)
![C](https://github.com/wolfi584/School_District_Analysis/blob/main/Resources/school%20size%20and%20scores.PNG?raw=true)
![D](https://github.com/wolfi584/School_District_Analysis/blob/main/Resources/scores%20by%20school%20size.PNG?raw=true)
![E](https://github.com/wolfi584/School_District_Analysis/blob/main/Resources/spending%20ranges%20per%20student.PNG?raw=true)

## Summary
In conclusion, removing the 9th and 10th grade reading and math scores from THS signifigantly affects many factors in the school district performance analysis. School rankings within the district, overall passing district percentage, a decrease in average THS math/science scores, and a potential change in funding for THS are all factors that change simple from removing two scores.

In order for each school and for the district to receive the funding they truly deserve, there needs to be a fast solution for this situation. Test scores are not the only item that determine school budgeting; school size, passing rates, and school type potentially affect how much each school will receive. 
