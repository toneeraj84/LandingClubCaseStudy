# LendingClubCaseStudy

Goals of data analysis:

Lending loans to ‘risky’ applicants is the largest source of financial loss
(called credit loss). The credit loss is the amount of money lost by the lender 
when the borrower refusesto pay or runs away with the money owed.  

The main objective is to be able to identify these risky loan applicants, 
then such loans can be reduced thereby cutting down the amount of credit loss. 
Identification of such applicants using EDA is the aim of this case study.   

Perform an analysis to understand the driving factors (or driver variables)
behind loan default, i.e.the variables which are strong indicators of default.  
The company can utilise this knowledge for its portfolio and risk assessment. 

Following are different analysis steps followed on the dataser provided:
Step 1: Data Cleaning 1
Step 2: Univariate Analysis
Step 3: Segemented Univariate Analysis
Step 4: Bivaraiate/Multivariate Analysis
Step 5: Insights and Recommendations

Insights:
The analysis of charged-off loans reveals a higher probability of default in the following cases:

- Applicants with an income between 60k and 70k who take out loans for "home improvement."
- Applicants with "MORTGAGE" as their home ownership status and an income of 60k-70k.
- Applicants earning 70k-80k who receive an interest rate of 21-24%.
- Applicants with loan amounts between 30k and 35k, charged an interest rate of 15-17.5%.
- Applicants taking loans for small businesses with amounts exceeding 14k.
- Applicants with "MORTGAGE" home ownership and loan amounts between 14k and 16k.
- Applicants with a grade of "F" and loan amounts ranging from 15k to 20k.
- Applicants with 10 years of employment and loan amounts between 12k and 14k.
- Verified loans with amounts over 16k.
- Applicants with a grade of "G" and interest rates above 20%.

### Recommendations:
Screening House Ownership:
 Avoid high-risk applicants with house ownership status marked as 'RENT' or 'MORTGAGE' (especially when income is within the 60k-80k range), as these applicants have shown a higher likelihood of default.
 
### Loan Purpose & Debt Consolidation:
 Prioritize applicants with loan purposes other than debt consolidation, home improvement, or small business loans, as these purposes are associated with higher default rates.
 
### Interest Rate Caps:
Set a maximum interest rate cap below 13%, as applicants charged rates in the 13-24% range are more prone to defaulting.

### Income Range Filters:
Avoid applicants with an income range of 31,201 - 58,402 and 60k-80k, especially when paired with loans for home improvement or other non-essential uses, as these income brackets appear at higher risk.

### Loan Amount Control:
Be cautious with applicants seeking loans between $5,429 - $10,357 or $15k - $35k, particularly those with a DTI ratio between 12-18 and monthly installments in the range of 145 - 274.

### Employment Length Verification:
Ensure that applicants' employment length is verified and consider lengthier employment as a factor. 10 years of employment is a critical cutoff point, with higher risk associated with longer durations.

### Credit Enquiries and Records:
Avoid applicants with 0 inquiries in the last 6 months and no derogatory public records—counterintuitively, this indicates a higher likelihood of defaulting. Verified records and inquiries are essential.

### Loan Term Limit:
Prefer shorter loan terms. Defaults are more common in 36-month terms.

### Lower Grade Applicants:
Be more cautious with applicants in Grade B, B5, F, and G. 
Defaults increase when loans are issued to these grades, especially with high loan amounts or interest rates exceeding 20% for Grade G applicants.



Contributors

    Santoshkumar Vagga
    Neeraj Kumar

Developed as part of the Exloratory Data Analysis Module required for Executive Post Graduate Programme in Machine Learning and AI - IIIT, Bengaluru -2024-25.
