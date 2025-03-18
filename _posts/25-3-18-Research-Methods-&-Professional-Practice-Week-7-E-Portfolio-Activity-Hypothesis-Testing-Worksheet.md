---
layout: post
title: Research Methods & Professional Practice, Week 7, E-Portfolio Activity, Hypothesis Testing Worksheet
subtitle: E-Portfolio Activity, Hypothesis Testing Worksheet
categories: Week 7

--- 

## E-Portfolio Activity, Hypothesis Testing Worksheet

## Hypothesis Testing Worksheet

For this e-portfolio exercise, students were required to partake in the hypothesis testing using Excel, in the Unit7 workbooks. 
For the first exercise, the instructions were as follows:
7.1 Containers
Consider the container design using two variables Con1 and Con2 (the number of items sold). We conduct a two-tailed related samples t test of whether the underlying (population) mean number of items sold differs between the two container designs. Students were to follow the worksheet excel instructions and conduct a data analysis “t test: Paired two samples for means”. The result:

![7 4F](https://github.com/user-attachments/assets/1a2d684e-af98-41f4-a67e-da46e7b66b1e)


The data therefore suggests strong evidence that, on a one-tailed test, the underlying mean number of containers sold was greater for Design 1 (Con1).

Exercise Question: Recall that in the previous exercise, a two-tailed test was undertaken whether the population mean impurity differed between the two filtration agents in Data Set G. Suppose instead a one-tailed test had been conducted to determine whether Filter Agent 1 was the more effective. What would your conclusions be?

Exercise Answer: Because the two-tailed p value of 0.0183 falls below the standard significance threshold of 0.05, and the one-tailed p value is 0.009, it suggests that there is no real difference between the two means.

7.1 Diet
For this exercise, students were to test whether the population mean weight loss differs between two diets. Since separate samples of individuals undertook the two diets, the independent samples t test is appropriate here. Students were to follow the worksheet excel instructions and conduct a data analysis “f test: Two sample for variances”. The result:

![7 6B1](https://github.com/user-attachments/assets/c5c93755-7cab-447d-9b43-db8d4690e131)

The data is consistent with the assumption that the population variances underlying the weight losses under the two diets do not differ, and therefore proceed to use the equal variances from the unrelated sample t test.

To test if the population mean weight loss differ between the two diets, a two-tailed t test was conducted. The result:

![7 6B2](https://github.com/user-attachments/assets/b16d3281-4d72-43e1-8c13-774d0fc2d951)

The obtained samples t=3.072 with 98 degrees of freedom. The associated two-tailed value is p=0.0028, so the observed t is significant at the 1% level (two-tailed). The sample mean weight losses for Diets A and B were 5.341 kg and 3.710 kg. The data therefore suggests that the underlying mean weight loss was greater for Diet A, by an estimated 5.314 – 3.710 = 1.631 kg. The results strongly suggest that Diet A is more effective in producing a weight loss. 

7.2 Bank cardholder data
In this exercise, students were to complete an appropriate test of whether the population mean income for males exceeds that of females (assuming the data is suitably distributed) and interpret the findings. 
I could not find the spreadsheet for this exercise on my portal. 


7.3 Statistics
For the next exercise, students were to repeat the previous exercises, however the variables Con1 and Con2 measure the same characteristics (number of items sold), but under two different “conditions” (two different container designs). The test conducts a two-tailed related samples t test of whether the underlying (population) mean number of items sold differs between the two container designs.
The result:

![7 4F2](https://github.com/user-attachments/assets/8b22aa1b-53fb-43d2-b769-afffbd2a04cf)

The obtained related sample t=2.875 with 9 degrees of freedom. The associated two-tailed p value is p=0.018, so the observed t is significant at the 5% level (two-tailed). The sample mean numbers of items sold for container Designs 1 and 2 were 172.6 and 159.4. The data therefore suggests evidence that the underlying mean number of containers sold was greater for Design 1, by an estimated 172.6 – 159.4 = 13.2 items per store. The result suggests that Design 1 should be preferred.

7.4 
For the next exercise, students were to repeat the previous exercises, where a two-tailed test was undertaken of whether the population mean impurity differs between the two filtration agents in Data set G. However, this time, the test to be conducted was a one-tailed test to determine whether Filter Agent 1 was the more effective. 
I could not find the spreadsheet for this exercise on my portal. 

7.5
For this exercise, students were to test whether the population mean weight loss differs between two diets. Since completely two separate samples of individuals undertook two diets, the independent sample t test is appropriate here. The result:

![7 6B3](https://github.com/user-attachments/assets/e0554eba-9d14-4b81-9c38-194621241295)

The sample variances for the two diets are 6.429 and 7.668. The observed F test statistic is F = 0.839 with 49 and 49 associated degrees of freedom, giving a two tailed p-value of p = 0.5399. 

Since the test was to see if the population mean weight losses differ between the two diets, a two-tailed t test is appropriate here.

Formula 1 =TTEST(data1;data2;mode;type). Here the first two are self-explanatory, mode indicates whether it is a 1 tailed test (1) or a two tailed test (2), type indicates whether it is a paired t test (1), an equal variances independent t test (2) or and unequal variances independent t test (3). This then returns the p-value for the chosen test.

As we have chosen a two tailed test then our formula will read =TTEST(B2:B51,B52:B101,2,2). We have shown above that we can assume equal variances.
The output is as follows:

Two-tailed 0.00275154 P-value 
One-tailed 0.00137577 P-value

The associated two-tailed p-value is p = 0.0028, so the observed t is significant at the 1% level (twotailed). The sample mean weight losses for Diets A and B were, respectively, 5.341 kg and 3.710 kg. The data therefore suggests evidence that the underlying mean weight loss was greater for Diet A, by an estimated 5.314 – 3.710 = 1.631 kg. The results strongly suggest that Diet A is more effective in producing a weight loss.







