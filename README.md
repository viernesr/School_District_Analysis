# School District Analysis

## Overview
A school board has requested Maria to provide a list of deliverables regarding a school district, mainly involving the district's key metrics, in regards to scores, rankings, and school performance based on budget, school size, and type of school. The deliverables were submitted to the school board, with the file being located [here](./PyCitySchools.ipynb). However, the school board has notified Maria and her supervisor there has been some academic dishonesty, more specifically the grades of ninth graders from Thomas High School being altered. Maria has requested to replaced all those scores affected with null values, while the rest of the data remain the same. Afterwards, a repeat of the analysis was done, this time with the changes being applied.

## Results
The following will describe how the modifited data affects the key metrics:
* Thomas High School still remains as the 2nd ranked school within the school district, however, the overall passing percentage closer to 3rd place, Griffin High School.
* Obviously with the changes being applied, the ninth graders of Thomas High School cannot be compared its fellow peers at the other schools within the school district, as all math scores from them have been listed as "NaN".
* The same is said from above in regards to reading grades.
* When looking at the average scores and percentages of passes based on school budget per student, the only differences are within the $630-$644 range, where the numbers are different with the modified data. While the average math and reading scores decreased, the percentage of students passing math, reading, and both have increased.
* Looking at the average scores and percentages of passes based on school size, the only differences are within the Medium size range (1000-2000). All but the average reading score have increased.
* Since Thomas High School is a Charter-type school, the Charter statistics have been affected. Just like the previous bulletpoint, all but the average reading score have increased. However, since the tables are formatted to one decimal point for score and 0 decimal points for percentage, they both show the exact same (rounded) values.

## Summary
The changes within the data showed that the guilty party cannot be compared to their fellow ninth graders from other schools, as they do not have any value listed under their scores. Within the budget range $630-$644, the scores decreased, but the percentage of students passing have increased. The school size statistics affected the Medium-sized grouping, where all but the average reading score increased.
