# ZINDI-Expresso-Churn-Prediction-Challenge
This was a challenge by ZINDI. I have uploaded the code here only because the challenge was completed and the winners were rewarded.

I have used different approaches to solving the problem noting the scores of the models at the end of each .ipynb file as a comment

Below is the information about the challenge

############################################################################################################

Description
Expresso is an African telecommunications company that provides customers with airtime and mobile data bundles. The objective of this challenge is to develop a machine learning model to predict the likelihood of each Expresso customer “churning,” i.e. becoming inactive and not making any transactions for 90 days.

This solution will help Expresso to better serve their customers by understanding which customers are at risk of leaving.

About Expresso:


Expresso is an African telecommunications services company that provides telecommunication services in two African markets: Mauritania and Senegal. Expresso offers a wide range of products and services to meet the needs of customers.

Rules
Teams and collaboration

You may participate in competitions as an individual or in a team of up to four people. When creating a team, the team must have a total submission count less than or equal to the maximum allowable submissions as of the formation date. A team will be allowed the maximum number of submissions for the competition, minus the total number of submissions among team members at team formation. Prizes are transferred only to the individual players or to the team leader.

Multiple accounts per user are not permitted, and neither is collaboration or membership across multiple teams. Individuals and their submissions originating from multiple accounts will be immediately disqualified from the platform.

Code must not be shared privately outside of a team. Any code that is shared, must be made available to all competition participants through the platform. (i.e. on the discussion boards).

The Zindi user who sets up a team is the default Team Leader. The Team Leader can invite other data scientists to their team. Invited data scientists can accept or reject invitations. Until a second data scientist accepts an invitation to join a team, the data scientist who initiated a team remains an individual on the leaderboard. No additional members may be added to teams within the final 5 days of the competition or the last hour of a hackathon, unless otherwise stated in the competition rules

A team can be disbanded if it has not yet made a submission. Once a submission is made individual members cannot leave the team.

All members in the team receive points associated with their ranking in the competition and there is no split or division of the points between team members.

Datasets and packages

The solution must use publicly-available, open-source packages only. Your models should not use any of the metadata provided.

You may use only the datasets provided for this competition. Automated machine learning tools such as automl are not permitted.

You may use pretrained models as long as they are openly available to everyone.

The data used in this competition is the sole property of Zindi and the competition host. You may not transmit, duplicate, publish, redistribute or otherwise provide or make available any competition data to any party not participating in the Competition (this includes uploading the data to any public site such as Kaggle or GitHub). You may upload, store and work with the data on any cloud platform such as Google Colab, AWS or similar, as long as 1) the data remains private and 2) doing so does not contravene Zindi’s rules of use.

You must notify Zindi immediately upon learning of any unauthorised transmission of or unauthorised access to the competition data, and work with Zindi to rectify any unauthorised transmission or access.

Your solution must not infringe the rights of any third party and you must be legally entitled to assign ownership of all rights of copyright in and to the winning solution code to Zindi.

Submissions and winning

You may make a maximum of 10 submissions per day.

You may make a maximum of 300 submissions for this competition.

Before the end of the competition you need to choose 2 submissions to be judged on for the private leaderboard. If you do not make a selection your 2 best public leaderboard submissions will be used to score on the private leaderboard.

Zindi maintains a public leaderboard and a private leaderboard for each competition. The Public Leaderboard includes approximately 20% of the test dataset. While the competition is open, the Public Leaderboard will rank the submitted solutions by the accuracy score they achieve. Upon close of the competition, the Private Leaderboard, which covers the other 80% of the test dataset, will be made public and will constitute the final ranking for the competition.

Note that to count, your submission must first pass processing. If your submission fails during the processing step, it will not be counted and not receive a score; nor will it count against your daily submission limit. If you encounter problems with your submission file, your best course of action is to ask for advice on the Competition’s discussion forum.

If you are in the top 20 at the time the leaderboard closes, we will email you to request your code. On receipt of email, you will have 48 hours to respond and submit your code following the submission guidelines detailed below. Failure to respond will result in disqualification.

If your solution places 1st, 2nd, or 3rd on the final leaderboard, you will be required to submit your winning solution code to us for verification, and you thereby agree to assign all worldwide rights of copyright in and to such winning solution to Zindi.

If two solutions earn identical scores on the leaderboard, the tiebreaker will be the date and time in which the submission was made (the earlier solution will win).

If the error metric requires probabilities to be submitted, do not set thresholds (or round your probabilities) to improve your place on the leaderboard. In order to ensure that the client receives the best solution Zindi will need the raw probabilities. This will allow the clients to set thresholds to their own needs.

The winners will be paid via bank transfer, PayPal, or other international money transfer platform. International transfer fees will be deducted from the total prize amount, unless the prize money is under $500, in which case the international transfer fees will be covered by Zindi. In all cases, the winners are responsible for any other fees applied by their own bank or other institution for receiving the prize money. All taxes imposed on prizes are the sole responsibility of the winners. The top 3 winners or team leaders will be required to present Zindi with proof of identification, proof of residence and a letter from your bank confirming your banking details. Winners will be paid in USD or the currency of the competition. If your account cannot receive US Dollars or the currency of the competition then your bank will need to provide proof of this and Zindi will try to accommodate this.

You acknowledge and agree that Zindi may, without any obligation to do so, remove or disqualify an individual, team, or account if Zindi believes that such individual, team, or account is in violation of these rules. Entry into this competition constitutes your acceptance of these official competition rules.

Zindi is committed to providing solutions of value to our clients and partners. To this end, we reserve the right to disqualify your submission on the grounds of usability or value. This includes but is not limited to the use of data leaks or any other practices that we deem to compromise the inherent value of your solution.

Zindi also reserves the right to disqualify you and/or your submissions from any competition if we believe that you violated the rules or violated the spirit of the competition or the platform in any other way. The disqualifications are irrespective of your position on the leaderboard and completely at the discretion of Zindi.

Please refer to the FAQs and Terms of Use for additional rules that may apply to this competition. We reserve the right to update these rules at any time.

Reproducibility of submitted code

If your submitted code does not reproduce your score on the leaderboard, we reserve the right to adjust your rank to the score generated by the code you submitted.
If your code does not run you will be dropped from the top 10. Please make sure your code runs before submitting your solution.
Always set the seed. Rerunning your model should always place you at the same position on the leaderboard. When running your solution, if randomness shifts you down the leaderboard we reserve the right to adjust your rank to the closest score that your submission reproduces.
We expect full documentation. This includes:
All data used
Output data and where they are stored
Explanation of features used
A requirements file with all packages and versions used
Your solution must include the original data provided by Zindi and validated external data (if allowed)
All editing of data must be done in a notebook (i.e. not manually in Excel)
Environment code to be run. (e.g. Google Colab or the specifications of your local machine)
Expected run time for each notebook. This will be useful to the review team for time and resource allocation.
Data standards:

Your submitted code must run on the original train, test, and other datasets provided.
If external data is allowed, external data must be freely and publicly available, including pre-trained models with standard libraries. If external data is allowed, any data used should be shared with Zindi to be approved and then shared on the discussion forum. Zindi will also make note of the external data available on the data page.
Packages:
You must submit a requirements file with all packages and versions used.
If a requirements file is not provided, solutions will be run on the most recent packages available.
Custom packages in your submission notebook will not be accepted.
You may only use tools available to everyone i.e. no paid services or free trials that require a credit card.
Consequences of breaking any rules of the competition or submission guidelines:

First offence: No prizes for 6 months and 2000 points will be removed from your profile (probation period). If you are caught cheating, all individuals involved in cheating will be disqualified from the challenge(s) you were caught in and you will be disqualified from winning any competitions for the next six months and 2000 points will be removed from your profile. If you have less than 2000 points to your profile your points will be set to 0.
Second offence: Banned from the platform. If you are caught for a second time your Zindi account will be disabled and you will be disqualified from winning any competitions or Zindi points using any other account.
Teams with individuals who are caught cheating will not be eligible to win prizes or points in the competition in which the cheating occurred, regardless of the individuals’ knowledge of or participation in the offence.
Teams with individuals who have previously committed an offence will not be eligible for any prizes for any competitions during the 6-month probation period.
Monitoring of submissions

We will review the top 20 solutions of every competition when the competition ends.
We reserve the right to request code from any user at any time during a challenge. You will have 24 hours to submit your code following the rules for code review (see above). Zindi reserves the right not to explain our reasons for requesting code. If you do not submit your code within 24 hours you will be disqualified from winning any competitions or Zindi points for the next six months. If you fall under suspicion again and your code is requested and you fail to submit your code within 24 hours, your Zindi account will be disabled and you will be disqualified from winning any competitions or Zindi points with any other account.
Evaluation
The evaluation metric for this challenge is Area Under the Curve (AUC).

The values can be between 0 and 1, inclusive. Where 1 indicates the customer churned and 0 indicates the customer stayed with Expresso.

The submission file is large, please expect a longer scoring time.

Your submission should look like:

user_id                                      CHURN
00001dbe00e56fc4b1c1b65dda63de2a5ece55f9      0.98
000055d41c8a62052dd426592e8a4a3342bf565d      0.12
000081dd3245e6869a4a9c574c7050e7bb84c2c8      0.37 
 
 
Prizes
1st Place: $500 USD

2nd Place: $300 USD

3rd Place: $200 USD

Zindi will award 2000 points for this competition, distributed as normal.

Timeline
Competition closes on 28 November 2021.

Final submissions must be received by 11:59 PM GMT.
