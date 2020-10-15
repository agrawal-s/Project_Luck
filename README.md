# Project_Luck
Experiment to study the role of luck in a typical competitive assessment.


It is often claimed that luck plays as important role as other things like talent, skills, wealth etc. But is this claim actually true? Could luck actually help you in a competitive selection process?

University of Catania designed a model talent show under the study where they tried to analyse the role of luck in success of the participants.

The results from the analysis show that it wasn't those regarded as the most talented that became wealthiest, but rather those regarded as the luckiest.
I have tried to replicate the study to the interview selection process. Using Monte-Carlo simulations, I have designed an experiment as follows:
> Each interview takes in 10000 applicants. Each applicant has attributes like Applicant_ID, skills_score, luck_score and overall_score. 
> Luck contributes to 5% of the overall score while the rest is the skills_score.
> In each interview, 10 applicants are selected. Their mean luck score is noted and appended to a list. The process is repeated 1000 times.
> Final list is studied and the results are discussed.

