# matplotlib_challenge

This challenge was one of the most difficult challenges I have had in the past 5 weeks. Since is the recap of Python, Pandas and Matplotlib, I had to spend countless hours reviewing the recorded classes, searching online, doing activities, and asking my peers for explanation to be able to make it on time. You will recognize that my code is very large and sometimes not efficient at all. I apologize for that; I still struggle with the use of loops and making them work properly. 

A total of 249 mice identified with SCC tumors were being put in an animal study by Pymaceuticals Inc. During 45 days, tumor development was observed and documented. Capomulin is the drug or interest.
Assumptions:
1. Assumed that each mouse can only have 1 mouse id and it won't change withing the study.
2. Assumed that all mice had identical living conditions, so that their performance is 100% comparable.

Code:
This working file has multiple named dataframes. Key items to consider is that cleaned_data_df refers to the combined dataframe without duplicates.
Because there are 4 main drugs of interest, you will find variables names as such. 
Group by is my main code in this workbook. Since the idea was mostly to analyze the data filtered and grouped by drug, mouse id, and tumor volume, I relied on ".groupby" to make it work.
Treatment is the same as drug, drug regimen, medicament. Whenever you see these titles, please know that is refering to the same thing.

Notes:
* Since I still struggle with the loops, I asked Krishna to explain it to me. We did the outliers calculation together. However, my script is not working correctly. I did 4 separate dataframes to calculate mean, median, variance, standard deviation and SEM. After that, I realized that I could not merge them all with the cleaned_data_df so I tried to do the loop on the 4 drugs only, and store the tumor volume in a variable but it is not working for me. ****Therefore, you will notice the Boxplot missing in my assignment.****
* The majority of this workbook was made together with Ricardo Varela. Our communication channel was always Slack, and we had our phone calls on that App for transparency with the University, in case you want to verify it.
* I still have difficulties with my cloned git for this assigment. It was always showing as master. After speaking to the instructor, it was advised to create a new one. However, I tried to push my work into the new one and I am still facing some issues that I will solve before the deadline. This is the reason why you won't be able to see my progress in git hub. This is another item to get better at, still not fully competent using Github.

Links used:
variance function in python: https://www.educative.io/answers/what-is-the-var-function-in-python
rotation of x labels using pyplot method: https://www.pythoncharts.com/matplotlib/rotating-axis-labels/

Laura
 


