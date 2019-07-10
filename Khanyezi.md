# 1. Executive Summary
We aim to empower communities to invest in their youths, through decentralized finance. We will do this by offering obligation-free student loans to post-graduate students and repackaging the loans into tradable securities for investors to invest in. This is done by tokenization.

We believe that the current student loan system is South Africa excludes many students with potential, as they often require a guarantor to co-sign their student loan. We will create a risk model which will project the likelihood of the student becoming employed once graduated and their income, this will allow us a place an informal credit rating on each student. This will be done using curated student data and to train a logistic regresion model for the likelihood of employment, and a linear regression for the income prediction. We believe that these models allow for simplicity, and transparency in our decision-making.

Once the model has selected students to whom we will award funding, we will raise the funds using a special purpose vehicle (SPV), to target investors of varying risk apetites. The overall credit rating of the pool will be determined by the overall credit rating of the students in the SPV. By aggregating many loans together, the overall funds become more predictable, which will yield a more attractive risk-adjusted return on investment.

We will tokenize the SPV to allow for easy trading between investors of the tokens. Investing in Khanyezi will allow investors to make a social impact, as well as diversify their portfolio. The SPV will be divided into three tranches:
* Senior tranche - lowest risk and lowest return for the investor
* Mezzzanine tranche - medium risk and return
* Equity tranche - will act similar to an equity product, where the return will depend on the number of defaults. This will be for the high risk investors. 

In our first year of business, we plan to onboard the University of Cape Town,and offer up to 50 students a loan. From there we wish to grow and eventually offer our product throughout South Africa. 

# 2. Company Description
## Company mission statement
Khanyezi is a company that connects post-graduate students and investors. Our aim is to create more viable interest rates for students on their student loans and simultaneously create a more secure investment for the investors. We also aim to increase access to funding as traditional funding sources tend to require a guarantor and interest repayments during their studies.

## Company philosophy and vision
Values: Integrity, Transparency, Community.

Vision: Removing barriers to education by providing affordable funding.

## Company goals
### Short term:
* Sign data agreements with University of Cape Town
* Onboard 50 students
* Create relationships with 5 potential employers for funded graduates

### Long term:
* Sign data agreements with 2 more universities
* Onboard 500 students
* Create a careers service platform to integrate with the funding platform
* Create a student ambassador program to create a presence on the platform

## Target market
Our target customers will be post-graduate students and social impact investors.

#### Post-graduate students 
At the beginning we will offer our services to post-graduate students only, this includes honors and masters students. We will offer obligation free loans i.e. their only commitment is to repay the loan. 

#### Investors
Different types of investors will be targeted by our funding structure. The amount of finance required will grouped together to create a pool of loans which will be separated into 3 tranches:
* Senior tranche (low risk, low return)
* Middle tranche (medium risk, medium return)
* Subordinate tranche (high risk, high return)

Targeting social impact investors allows us to keep fees low, and will give them the opportunity to invest their money in an investment that will have some social impact. There are many portfolios who aim to have a certain percentage of their funds invested in social impact investment.

We believe that there will be a market here as the current loans have excessively high administration costs 
as well as high interest costs.

## Industry
We believe that we will have a competitive advantage due to the current industry structure. Our current competitors are the major banks, for example Standard Bank, ABSA, FNB and NedBank and any other organization offering student loans. These institutions require a guarantor earning at least R3,000 and the guarantor is obliged to make interest payments while the student is studying. It is often difficult for students to find someone to agree with this, especially those from low or no income families.The interest payments are often burdensome for guarantors earning as little as R3,000.

We also believe that there is a plethora of unused student-specific data which has been overlooked by these incumbents due to lack of access to or knowledge of such data. The traditional application process is long, we aim to reduce application time to minutes for most applications. The current structure also excludes individual investors from participating and we aim to increase access to this investment vehicle.

Our business will have a competitive edge because we will base our loans on non-traditional student information, for example:
* Academic performance
* Degree
* Years to complete degree
* Extra-curricular activities
* Graduate employment rate – faculty/department 
* Institution 
* Industry data (e.g. from OfferZen)

This will allow us to model the probability of a particular student being employed after their studies which is correlated with their likelihood of being able to repay the loan. From this we will be able to apply credit rating to the students, which will allow us to make better decisions about the funding, based on the students future potential income. No weight will be placed on their current financial situation and we open loans to a broader number of students, who would otherwise not be eligible for loans and face financial exclusion in the current system. 

In the long term we are aim to offer customised student loan structures that suit the relevant industry in which the graduate is employed, packaging them in such a way that maximizes the likelihood of repayment. As an example it is a well known fact that students completing their law articles earn R10,000 - R12,000 per month during their articles, but their salaries increases once they are done. A customised papyment plan would allow for low repayments during their articles, and increase thereafter.

We also hope to assist the government, and bursary schemes in making better investment decisions, and allocating according to potential.
We believe that our platform would also incentivise repayment due to its transparent nature.

# 3. Products and Services

## Our products and services
We offer collateral-free loans to post-graduate students by creating a social investment product that allows multiple investors to participate in funding their studies. These loans are packaged into investible products that investors can purchase. 

The process can be explained as follows:

[![Presentation02fa25524f1ba1b7.md.png](https://imgbbb.com/images/2019/07/05/Presentation02fa25524f1ba1b7.md.png)](https://imgbbb.com/image/ZcdhR)

* Step1: 
The model assigns probability of the student getting a job after graduation (which simultaneously applies a credit rating to that student).

* Step 2:
The model decides on a cut off for which students to give loans, which will be decided by an overall credit rating we want to achieve for the pool of funds.

* Step 3: Securitise the funds into publicly traded securities by:
  * creating 3 tranches out of the overall loan fund into which potential investors can decide to invest. 
  * These are created by offering publicly tradable tokens, where each of the 3 tranches has a different token:
    * KhanyeziSenior
    * KhanyeziMezzanine
    * KhanyeziEquity
  * One token will equal one rand, and these will accumulate value over time equivalent to the fixed interest rate the investor will earn on their security
  * Once the student has a job, they will repurchase their higher valued tokens from the investors. 
Each year a new investable fund will be created.

#### Why tokens?
This will allow us to attract investors who want to invest in any amount (and currency) into this fund (small or large), as tokens will allow us to split the loans into securities that can be traded on the secondary market. Basically we will create a liquid asset out of an illiquid asset (loans). The process of tokenization allows for fractionalization so that the lender can sell any portion and at any time. 

This will also make investing easier and cheaper for the average investor. 

In summary, this will allow:
* Liquidity where otherwise not possible
* Fractional ownership
* Frictionless transaction: the governing system of token transfers is based on smart contracts and can be automated. This will allow for real time execution and low transaction fees. 
* Transparency in the value chain: Blockchain as technology brings transparency and immutability to all records.
* Greater access: opens access to smaller and large investors,and all currencies.

#### Repayment structure

1. Student pays fiat into our bank account using unique reference #
2. Reference number and Amount paid is recorded by Oracle - a nodejs service  using request library to fetch deposit info
3. Oracle uses an API to get latest ZAR/ETH price 
4. Parsed data is submitted as a transaction and sent to smart contract
5. Smart contract processes

#### Smart contracts

* smart contracts can be used to measure the investment risk of security pools
* notify investors/creditors when a mortgage has gone delinquent
* and determine the value of securities in real time.

We will have 3 different specific use functions for the smart contract:
* Create token (3 slightly different ones)
* Investors to buy tokens (initially 1 token = 1 rand, as a stable coin)
  * Should increase inline with fix interest of loan, so that it is easily tradable
* Repayments of student

## Competitive advantage

Traditional loan and securitization process generally requires the input of many parties – creditors, underwriters, loan officers, etc. which drive up the administrative costs and make transparency difficult. There are large information asymettries that exist in these complex structures and the burden of this is often felt by the party taking out the loan, in the form of high interest rates.

Because we will be using the blockchain technology, we will be able to offer:
* Streamlined processes, lower costs, increase transaction speed, enhanced transparency
* Immutable audit trail: single source of truth that participants can use 
* Ability to track and manage payment records

We will also link the students and the investors together, which is usually not the case. We will create liquid loans and attract multiple investors, which will make the raising of the funds easier. 

## Pricing our product or service 
We will be a non-profit company, in order to assure that students get the best possible rates. However, we will have to price in any salaries, development costs and other expenses. It will be our aim to keep this as low as possible and we will be able to do this using blockchain technology. We will also allow for transparency in the fee structure. This will allow the students and investors to see where the fees are being used and that they are not being wasted. Students will be charged a small administration cost to cover the Gas for running the repayments smart contract. And investors will be charged a fee for Khanyezi to service the loans.

# 4. Marketing Plan
## Market research
### Current Industry

#### Private
Currently post-graduate students loans are mainly offered by the bank. 
For most of the loans, the students need to have a sponsor who is able to act as surety if they are unable to repay the loan. This limits the number of students who are able to apply for loans. We will have no such policy, as we will rely on our model. 

**ABSA**:
* Interest rate: all loans are at the prime rate. 
* Bank charges: R1 197 (including VAT) initiation fee (on first loan only) and R68.40 (including VAT) monthly administration fee.

**FNB**:
* Interest rate: Corne Jordaan, the head of credit at FNB Personal Loans, says the interest rate is linked to 
prime and based on the risk profile of the sponsor and the nature of studies. Rates offered to FNB 
customers are between prime and prime plus six percentage points
* Bank charges: An initiation fee of R165 per credit agreement, plus 10 percent of the amount in excess of R1 000, but not exceeding R1 050 plus VAT, or R1 197. The initiation fee is charged once; not repeated for subsequent years of study. The monthly administration fee on the loan is R68.40 (including VAT).

**Nedbank**:
* Interest rate: prime plus two percentage points.
During the period of study the guarantor is expected to service the interest due on the loan, and once the student has graduated and is employed, the student repays the full amount over an agreed period (up to 18 months per year of study funded).
* Bank charges: R75 initiation fee and no monthly administration fee. There is a R65 initiation fee for subsequent years of study. (Charges exclude VAT.)

**Eduloan**:

#### Public:
**NSFAS Student loans – Financial aid**:
* Interest rate: 80% of prime rate.  
(not really competitors, but rather possible partners)
They offer student loans to means tested and good academic performance. We could help them improve their model and attract investors to be able to offer more students funding. 

## Barriers to entry
We may face some issues due to high data needs to create a viable model. This is challenging as we need to get through a number of data sources and work on a model that best predicts a student’s credit rating. It is also a long, time consuming process to get the right ethics clearance to obtain and use that data. 

There may be a high start-up cost due to the model, app, website and technology development involved in this project. 

Additionally, we may need to do some test runs first for a couple of years to see how well our model predicts.

## Threats and opportunities
We may face the threat of investors not fully understanding and trusting our process and models. The government may also not trust our model and ban us from offering our services. More research and testing needs to be done here. 
Additionally we face the threat of not being able to abtain the needed data to produce a trusted model. 

However, due to the current student laon structures and need for student loans in South Africa, we see a lot of opportunity. Our mission aligns well with the government objective of increasing throughput through universities. We will be able to open more study opportunities for students and allow for investors to diversify their portfolios. 

## Product features and benefits
#### Most important feature:
* The loans will be securitized and tokenized to allow access to more investors and trading between them. This will also allow for transparency and lower loans costs for the students
* A model will be used to apply credit ratings to the students

#### Most important benefit
Cost savings and financial inclusion. This product is aimed not to exclude those students that have no one to stand surety for their loan, or any other financial surety. 

#### Possible after-sale services:
* Secondary market for investors to trade their tokens
* An app interface for the student to keep track of their loan and how much they still need to repay/have repaid already
* An app interface for the investor to see how much money is owed to them and when to expect repayment, and any other details (level of risk of investment)
* For both the student and investor to see how fees are being used and what the investment fund consists of (level of risk) to allow for full transparency. 

## How we will market our product initially
**Advertising may include:**
* On-campus events
* Brand ambassadors
* SRC
* Online

**Marketing may include:** 
* Business website
* Social media marketing
* Email marketing
* Search engine optimization
* Networking
* Word-of-mouth
* Referrals
* University campuses

## Costs

#### Initial costs
* Minimum capital requirement against the risk-weighted loans, to support the function of the SPV and act as a cushion. 
* There will be some initial development fees
 * Development costs
 * Research costs
 * Technological expenses
* There may be a license fee
* Initial launching and marketing fees
* Legal advice costs
* Since we are developing on the Ethereum platform, we will need to buy Ether, which may result in additional costs


#### Continued costs
* Labour costs
* Gas to run smart contracts













