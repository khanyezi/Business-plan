# 1. Executive Summary
### An overview of our business idea (one or two sentences)

### A description of your product and/or service. What problems are you solving for your target customers? 
### Your goals for the business. Where do you expect the business to be in one year, three years, five years? 
### Your proposed target market. Who are your ideal customers? 
### Your competition and what differentiates your business. Who are you up against, and what unique selling proposition will help you succeed? 
### Your management team and their prior experience. What do they bring to the table that will give your business a competitive edge? 
### Financial outlook for the business. If you’re using the business plan for financing purposes, explain exactly how much money you want, how you will use it, and how that will make your business more profitable. 

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
At the beginning we will offer our services to post-graduate students only, this includes honors and masters students. We will offer obligation free loans. 

#### Investors
Different types of investors will be targeted by our funding structure. The loan fees needed will grouped together to create a pool of funds which will be separated into 3 tranches:
* Senior tranche (low risk, low return)
* Middle tranche (medium risk, medium return)
* Subordinate tranche (high risk, high return)

Targeting social impact investors allows us to keep fees low, and will give them the opportunity to invest their money in an investment that will have some social impact. There are many portfolios who aim to have a certain percentage of their funds invested in social impact investment.

We believe that there will be a market here as the current loans have excessively high administration costs 
as well as high interest costs.

## Industry

We believe that we will have a competitive advantage due to the current industry structure. Our current competitors are the major banks, for example Standard Bank, ABSA, FNB and NedBank and any other organization offering student loans. These institutions require a guarantor earning at least R3,000 and the guarantor is obliged to make interest payments while the student is studying. It is often difficult for students to find someone to agree with this, especially those from low or no income families.

We also believe that there is a plethora of unused student-specific data which has been overlooked by these incumbents due to lack of access to or knowledge of such data. The traditional process is long and we aim to reduce application time to minutes for most applications. The current structure also excludes individual investors from participating and we aim to increase access to this investment vehicle.

Our business will successfully compete as we will base our loans on non-traditional information on the students, for example:
* Academic performance
* Degree
* Years to complete degree
* Extra-curricular activities
* Graduate employment rate – faculty/department 
* Institution 
* Industry data (e.g. from OfferZen)

This will allow us to model the probability of a particular student being employed after their studies and their likelihood of being able to repay the loan. From this we will be able to apply credit rating to the students, which will allow us to make better decisions about the funding, based on the students future potential income. No weight will be placed on their current financial situation and we open loans to a broader number of students, who would otherwise not be eligible for loans and face financial exclusion in the current system. 

In the long term we are aiming to be able to offer different students loan structures that suit their industry and package them in such a way to maximize likelihood of repayment.e

We hope to assist the government in making better investment decisions, and allocating according to potential.

# 3. Products and Services

## Our products and services
We offer collateral-free loans to post-graduate students by creating a social investment product that allows multiple investors to participate in funding their studies. These loans are packaged into investible products that investors can purchase. 

The process can be explained as follows:

![alt text](https://lh4.googleusercontent.com/7YutknJ-zOUtuNavpJHq2fjX5OIP6BRiQgnXMhu2FQTzlRpRkqREVD-DdnurIDVvsR1SqaoxmjVVAT3wqdFKXM1DoXF48NRSDxCWv6F8)

* Step1: 
The model assigns probability of the student getting a job after graduation (which simultaneously applies a credit rating to that student).

* Step 2:
The model decides on a cut off for which students to give loans, which will be decided by an overall credit rating we want to achieve for the pool of funds.

* Step 3: Securities the funds into publicly traded securities by:
  * creating 3 tranches out of the overall loan fund into which potential investors can decide to invest. 
  * These are created by offering publicly tradable tokens, where each of the 3 tranches has a different token:
    * KhanyeziSenior
    * KhanyeziMezzanine
    * KhanyeziEquity
  * One token will equal one rand, and these will accumulate value over time equivalent to the fixed interest rate the investor will earn on their security
  * Once the student has a job, they will repurchase there higher valued tokens from the investors. 
Each year a new investable fund will be created.

#### Why tokens?
This will allow us to attract investors who want to invest in any amount into this fund (small or large), as tokens will allow us to split the loans into securities that can be traded on the secondary market. Basically we will create a liquid asset out of an illiquid asset (loans). The process of tokenization allows for fractionalization so that the lender can sell any portion and at any time. 

This will also make investing easier and cheaper for the average investor. 

In summary, this will allow:
* Liquidity where otherwise not possible
* Fractional ownership
* Frictionless transaction: the governing system of token transfers is based on smart contracts and can be automated. This will allow for real time execution and low transaction fees. 
* Transparency in the value chain: Blockchain as technology brings transparency and immutability to all records.
* Greater access: opens access to smaller and large investors.

#### Repayment structure

1. Student pays fiat into our bank account using unique reference #
2. Reference number and Amount paid is recorded by Oracle - a nodejs service  using request library to fetch deposit info (from Banking API?)
3. Oracle uses an API to get latest ZAR/ETH price (do we need this?)
4. Parsed data is submitted as a transaction and sent to smart contract
5. Smart contract processes

#### Repayment structure

* smart contracts can be used to measure the investment risk of security pools
* notify investors/creditors when a mortgage has gone delinquent
* and determine the value of securities in real time.

We will have 3 different specific use functions for the smart contract:
* Create token (3 slightly different ones)
* Investors to buy tokens (initially 1 token = 1 rand, as a stable coin)
  * Should increase inline with fix interest of loan, so that it is easily tradable
* Repayments of student

## Competitive advantage

Traditional loan and securitization process generally requires the input of many parties – creditors, underwriters, loan officers, etc. which drive up the administrative costs and make transparency difficult. 

Because we will be using the blockchain technology, we will be able to offer:
* Streamlined processes, lower costs, increase transaction speed, enhanced transparency
* Immutable audit trail: single source of truth that participants can use 
* Ability to track and manage payment records

We will also link the students and the investors together, which is usually not the case. We will create liquid loans and attract multiple investors, which will make the raising of the funds easier. 

## Pricing our product or service 




