
# RoboAdvisor - Amazon Lex Bot

Sign in to your AWS Management Console, and then create a new custom Amazon Lex bot (Links to an external site.). Use the following criteria:
- Bot name: RoboAdvisor
- Language: English (US)

- Output voice: Salli

- Session timeout: 5 minutes

- Sentiment analysis: No

- COPPA: No

- Advanced options: No

- other options: The default value

Once the bot is created, add a new intent, and name it recommendPortfolio and configure sample utterances as follows (you can add more utterances if you want):

- I want to save money for my retirement

- I'm {age} and I would like to invest for my retirement

- I'm ​{age} and I want to invest for my retirement

- I want the best option to invest for my retirement

- I'm worried about my retirement, etc.


Create four slots: FirstName, Age, InvestmentAmount, RiskLevel

Move to the “Confirmation prompt” section, and then set the following messages:

Confirm: Thanks, now I will look for the best investment portfolio for you.

Cancel: I will be pleased to assist you in the future.


The builds that the Roboadvisor is working are as videos in seperate folder. 
