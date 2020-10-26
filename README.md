# School_District_Analysis
Analyzing school test scores to determine funding using Anaconda to analyze
# Overview
For this project Maria asked us to change Thomas High School scores for math and reading, in particular the 9th grade class. We are taking out the scores from this class due to the potential of academic dishonesty. We are replacing the scores with "NaN", after this is done we need to run the analyse over again to find the new results.
# What we Found
In order to do the analysis we needed to find certain data, the following is some of the data we found
- Total number of 9th graders attending Thomas High School
- Total number of students in the district without Thomas High School 9th grade class
- The average reading score of the district
- The average math score of the district
- The overall passing of the district
- The total passing at Thomas High School
- The total passing percentage at Thomas High School
# Changes That Were Made
1. Taking the 9th grade class out of Thomas High School caused many things to happen as a side effect, but it alone is a huge change.
!["Per School Summary"]("Resources/thomas_high_school.png")
2. The total students changes multiple different sets of data all throughout the analysis
3. Looking at the information again we found that the 5 lowest and 5 highest schools changed, with the 9th grade class taken away from the overall scores in Thomas High School the schools scores went up dramatically
!["Top 5 Performing Schools and Lowest 5 Performing Schools"]("Resources/5_lowest_and_5_highest.png")
4. The three dataframes at the end have entirely new data to work with now and can help to make more accurate desicions based on the data.
!["Spending Per Student"]("Resources/spending_per_student.png")
!["Size of School"]("Resources/school_size.png")
!["Type of School"]("Resources/school_type.png")
