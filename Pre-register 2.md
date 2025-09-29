---
tags:
---
### Have any data been collected for this study already?
No data has been collected for this study yet.
### What's the main question being asked or hypothesis being tested in this study?
**Main Research Question:**  How does disclosing the use of Generative AI at different stages (information gathering, analysis, recommendation) in preparing an investment report affect an investor's acceptance of the report's recommendation? 
### Describe the key dependent variables specifying how they will be measured.
The key dependent variable is the participant's incentivized investment decision. After reading the investment report, participants will be asked to choose one of three companies (disguised with pseudonyms) in which to invest. The report will explicitly recommend one of these three companies.

For the primary analysis, this categorical variable will be coded as a binary outcome:
- 1 = The participant chose the company that was explicitly recommended in the report.
- 0 = The participant chose one of the two other (i.e., non-recommended) companies.
### How many and which conditions will participants be assigned to?
Participants will be randomly assigned to one of four experimental conditions based on the presence and content of a "Generative AI Disclosure" section in an investment report. The disclosure specifies Generative AI use across three stages: information gathering, conducting analysis, and formulating recommendation.
- **No AI Use (`No/No/No`)**: The disclosure states that generative AI was not used for any of the three stages.
- **Full AI Use (`Yes/Yes/Yes`)**: The disclosure states that generative AI was used for all three stages.
- **Mixed AI Use**: The disclosure indicates a partial use of AI, where it was employed for one or two of the three stages ('Yes/No/No', 'No/Yes/No', 'No/No/Yes', 'Yes/Yes/No', 'Yes/No/Yes', 'No/Yes/Yes').
- **No Disclosure**: The report contains no "Generative AI Disclosure" section, and no information about AI use is provided.
### Specify exactly which analyses you will conduct to examine the main question/hypothesis.
In all models, I will use OLS regression analysis with a binary dependent variable (i.e. linear probability models).

**Primary analysis:** 
The primary analysis will focus on the four conditions to test the main research question regarding the impact of using AI at different stages. The 'NoAI/NoAI/NoAI' condition will serve as the baseline for these comparisons.

A set of models will be analyzed to examine the effects of specific experimental combinations. The main independent variables will be three binary variables, each representing a condition (Full AI Use, Mixed AI Use, No Disclosure). The 'NoAI/NoAI/NoAI' condition will be omitted to serve as the baseline reference group.

The coefficient for each binary variable will represent the change in the probability of following the recommendation for that specific condition, relative to the baseline. For example, a significant negative coefficient on the 'NoAI/AI/AI' binary variable would indicate a lower likelihood of participants following the recommendation under this condition (i.e., AI in analysis and recommendation stages only) compared to the baseline where AI is not used in any stage.

**Secondary analysis:** 
To explicitly test the effect of Generative AI disclosure itself, the secondary analysis will directly compare the 'No Disclosure' condition with the 'NoAI/NoAI/NoAI' condition. The analysis examines whether the showing AI disclosure has an effect on the probability that a participant will follow the report recommendation.
### Specify exactly how outliers will be defined and handled, and your precise rules for excluding observations.
Participants who fail to complete the entire survey or withdraw their consent for participation upon debriefing will be excluded from the analysis. Any participants answering more than once will also be excluded.

### How many participants will be recruited?
TO BE DETERMINED
### Anything else you would like to explore?
I will conduct a series of planned exploratory analyses to understand the potential mechanisms driving the results. 

**Exploratory Mechanism Analysis:** I will use mediation analysis to test whether the effect of the AI disclosure conditions on the investment decision is mediated by any of the following three potential mechanisms. The three proposed mediators are:

1. Evaluation Attention Shift
2. Distrust in Disclosure
3. Perceived Expertise, Benevolence, and Integrity

Mechanism 1 and 2 are each measured by a 7-point Likert-style survey item. Mechanism 3 is decomposed into three components: expertise, benevolence, integrity. Each component in Mechanism 3 is measured by multiple 7-point Likert-style survey items, which will be combined to form a scale. I will use causal mediation analysis to examine the mediation effects.

**Exploratory Moderation Analysis:** I will examine whether the main effect of AI disclosure is moderated by participants' demographic characteristics, including age, gender, occupation, income level, prior investment experience, and attitudes towards AI. I will include the interaction of each factor and the AI disclosure binary variable in the OLS regression. The coefficient of the interaction term is the moderating effect of demographic characteristics. 
