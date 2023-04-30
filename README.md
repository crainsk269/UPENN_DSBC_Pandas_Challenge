# UPENN_DSBC_Pandas_Challenge

When writing the code for the pandas_challenge, I used examples from the code we learned during class. Also, there was some code already provided for this challenge. Additionally, I referenced pandas.docs and numpy.org when necessary as well as Stack Overflow and a few YouTube videos (specifically on pd.cut). I found all resources to be helpful with the exception of Stack Overflow on this particular occasion. I also worked with a few classmates when doing some troubleshooting.

One error that took me a while to figure out turned out to simpy be a typo on my part. One of the files has the headers "reading_score" and "math_score", and I typed in "math_scores" instead. I examined every part of my code until I finally realized that my misspelling was the cause of my error. Also, I kept getting an error with my pd.cut line of code. I was troubleshooting with a classmate and we compared our code to see if we could figure out the problem. I was actually writing the code properly based on previous examples, however, I wasn't thinking that I had already created a variable for what I needed. After I used the variable then it worked correctly.

Code: school_spending_df['Spending Ranges (Per Student)'] = pd.cut(per_school_capita, spending_bins, labels=spending_labels)

All numbers match the expected output.
