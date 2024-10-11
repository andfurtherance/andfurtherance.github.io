---
layout: post
title: Understanding IFRS 9
blog_title: Understanding IFRS 9 Expected Credit Losses
date: 2024-10-11
category: risk management, credit risk
---
Imagine lending money to a friend. There's always a chance they might not pay it back. If they lose their job or run into trouble, they might not be able to give back what they owe. Now, instead of just one friend, picture lending money to hundreds or thousands of people. Basically, what banks do every day. When they lend, they always have to think about the possibility that some of these loans won't be repaid. This is where **IFRS 9** and **Expected Credit Losses** come in.

IFRS 9 is a set of rules that helps banks and other companies figure out how much money they might lose on their loans, based on the risk that some borrowers won't be able to pay back what they owe. ECL is the way banks estimate those possible losses. It's like trying to predict the future, but with a lot of math and careful thinking.

Why does it matter? Banks need to make sure they have enough money set aside to cover potential losses. If too many loans go bad and they don't have enough money to cover those losses, the bank could get into trouble.

## What is IFRS 9
IFRS 9 stands for International Financial Reporting Standard 9, and it's a set of rules that tells companies how to handle financial instruments like loans, bonds and other things that involve lending or borrowing money. It was introduced in 2014 to replace an older, less strict set of rules. The main reason IFRS 9 was created was to improve how companies deal with the risk of loans going bad.

Before IFRS 9, banks only had to worry about losses on loans when it was obvious that a borrower wasn't going to pay back the loan. This could be when the borrower missed several payments. The problem with this approach was that it didn't give a bank enough time to prepare for losses. If a lot of borrowers started defaulting at the same time, it could catch the bank off guard.

IFRS 9 fixed this by introducing the concept of Expected Credit Losses (ECL). Instead of waiting for loans to go bad, banks now have to think ahead and estimate how much they could lose in the future. They have to do this from the moment they make a loan, and they update their estimate regularly as situation changes.

## Expected Credit Loss
ECL is the amount of money a bank expects to lose on a loan over time. It's not a certain amount but rather an estimate of what might happen.

ECL is based on three key factors:
1. Probability of Default: This is the chance that a borrower will fail to pay back the loan.
1. Loss Given Default: This is how much the bank expects to lose if the borrower defaults. Even if the borrower defaults, the bank might still get back some of the money, maybe by selling collateral or through other means. LGD is the amount the bank thinks it won't recover.
2. Exposure at Default: This is the total amount of money the borrower owes at the time of default, including interest and other fees.

The formula for calculating ECL is simple.
$ ECL = PD * LGD * EAD $


> ### Example: lending Money to a Friend
> Imagine leading NPR 100 to a friend. There's a 10% they won't be able to pay it back. If they default, you think you'll lose about 70% of the loan because maybe you can get back some money by selling something they own . So:
> 1. PD = 10%
> 2. LGD = 70%
> 3. EAD  = NPR 100
> 
> Using the ECL formula:
> 
>$$ ECL = 0.10  * 0.70 * 100 = 7 $$

This means you expect to lose $7 on this loan. You might still get back NPR 7 on this loan. You might still get back NPR 93, but you're preparing for the possibility that you'll lose NPR 7.

Of course, banks don't just lend to one person--they lend to thousands of people and businesses. So they calculate ECL for every loan and add them up to estimate their total expected losses.
## Stages of Loans Under IFRS 9
IFR splits loans into three stages depending on how risky the loan is **at a given moment**. The stage a loan is in affects how the bank calculates its ECL.

### Stage 1: Performing Loans
When a bank first makes a loan, it assumes that the borrower is going to pay it back as expected. This is called a performing loan, and it's placed in Stage 1. Since the loan is performing well, the bank calculates ECL based on the next 12 months of the loan. This is called 12-month ECL.

For example. if a bank lends NPR 10,000 to a business, and the business is doing well, the bank assumes the loan is performing. The bank calculates how much it expects to lose over the next 12 months, based on the PD, LGD and EAD.

### Stage 2: Underperforming Loans
Sometimes, loans start to look a bit riskier. Maybe the borrower is struggling financially, or the economy is in trouble. The loan is still being repaid, but the chances of default have increased. This is called an underperforming loan, and it moves to Stage 2.

For Stage 2 loans, the bank calculates ECL based on the lifetime of the loan, rather than just the next 12 months. This is called lifetime ECL. The idea is that if a loan is riskier, the bank needs to think about the possibility of default over the entire life of the loan, not just the next year.

For example, if that same business starts missing payments or shows signs of financial trouble, the bank moves the loan to Stage 2 and recalculates ECL based on the lifetime of the loan, which might be five years or more.

### Stage 3: Non-performing Loans
When a borrower stops paying back the loan altogether, or it's clear that they won't be able to repay it, the loan becomes non-performing and moves to Stage 3. At this point, the bank is almost certain the borrower will default.

For Stage 3 loans, the bank still calculated lifetime ECL, but now it assumes that the PD is 100%--meaning the borrower will definitely default. The bank also focuses on how much it can recover after the default (the LGD).

If the business goes bankrupt and stops making payments, the bank moves the loan to Stage 3 and tries to figure out how much of the loan it will be able to recover by selling of the business's assets.

## How Banks Calculate ECL
Let's now explain how bank would calculate ECL for a portfolio of loans. The process involves several steps, and while the math can get complicated, the general idea is simple: the bank needs to estimate three things--PD, LGD and EAD--for each loan, then multiply them together.

### Step 1: Grouping Loans
Banks usually have thousands of loans, so they don't calculate ECL for each one individually. Instead, they group loans with similar characteristics. For example, they might group all home mortgages together, all car loans together, and all business loans together. This lets them estimate PD, LGD and EAD for each group, rather than for each individual loan.

### Step 2: Estimating PD, LGD and EAD
Once the loans are grouped, the bank estimates the PD, LGD and EAD for each group.

1. **PD**: The bank looks at past data to figure out how likely borrowers in each group are to default. For example, if 5 out of 100 borrowers with home mortgages defaulted last year, the bank might estimate a PD of 5% for home mortgages.
2. **LGD**: The bank estimates how much it can recover if a borrower defaults. For example, if the bank usually recovers 60% of a mortgage loan by selling the house, it would set LGD at 40%.
3. **EAD**: The bank calculates how much money is at risk.  This  is usually the outstanding balance of the loan.

### Step 3: Calculating ECL
Once the bank estimated PD, LGD and EAD for each group, it multiplies them together to calculate the ECL for each group. Then, the ECLs for all the groups are added up to get the total expected credit losses for the bank.

> ### Example: A Bank's Loan Portfolio
> Imagine a bank has two groups of loans: home loans and auto loans. The PD, LGD, and EAD for each groups are estimated as follows:
> - Home Loans
> - PD = 2%
> - LGD = 30% (the bank expects to lose 30% of the loan if there's a default)
> - EAD = NPR 50 crores (the total amount of outstanding home loans)
> - Auto Loans
> - PD = 5% 
> - LGD = 50%
> - EAD = NPR 10 crores
> 
> Now the bank calculates ECL for each group:
> - ECL for Home Loans
> $$ ECL = 0.02 * 0.30 * 500000000 = 3000000 $$
> ECL for Auto Loans
> $$ ECL = 0.05 * 0.50 * 100000000 = 2500000 $$
> 
> So the bank expects to lose NPR 55 lakhs across its loan portfolio.


## To Conclude
ECL helps banks prepare for the future. By estimating how much they might lose on loans, banks can set aside money to cover those losses. This makes them more stable and less likely to fail if a lot of borrower default at the same time.

IFRS 9 and ECL are also important because it forces you to think about possible losses earlier. Instead of waiting for loans to go bad, banks now have to estimate losses from the moment they make a loan. This helps precent surprises.

ECL is about being realistic. Not everyone will pay back their loans, so instead of hoping for the best, they prepare for the worst. And by doing the math, they can get a pretty good idea of what to expect.
