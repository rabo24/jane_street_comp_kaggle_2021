# jane_street_comp_kaggle_2021

Jane Street provided a 2.4 million observation dataset that consisted of 130+ features and asked us to build an algorithm that would determine under what situations we should execute the trade. The sum of our trading decisions will be graded on a utility function determined by Kaggle. 
I broke the code down into two parts: exploratory data analysis and my submission code. For the submission code I used a random forest algorithm. I wanted to use a stochastic gradient boost algorithm but my computer doesn't have enough computing power to train the treeboost on a dataset of this size. To train the random forest I took a small sample of the 2.4M observation dataset(about 50k transactions).
