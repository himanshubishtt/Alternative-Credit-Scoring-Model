# Alternative-Credit-Scoring-Model
A loan is a sum of money borrowed that is expected to be paid back with interest. Whether buying a house, owning your dream car, providing children the best education possible or paying the bills, getting a loan is one of the most common actions that are taken by an individual at some point of their life. It reduces financial pressure for a while and helps direct focus on other important goals, thereby making life easier. <br/>
Traditionally, a credit score is assigned to each individual that determines whether this person is a trusthworthy borrower or not. It uses various metrics like credit repayment history, credit utilization, credit mix etc. which directly influence it. <br/>
But what if an applicant has no previous credit history ? <br/>
Is he/she eligible for a loan ? <br/>
How can this applicant be scored ? <br/>
This is where an alternative credit scoring model comes in. It can be used to determine whether a fresh applicant is eligible to get a loan or not. It scores an applicant between 0-900 and helps in deciding whether the applicant can be a trusthworthy borrower or not. It helps both the borrower and the lender by initializing the former's credit history and allowing the latter to make more money. <br/>
The alternative credit scoring model I have made uses a custom dataset made using Python libraries and using various machine learning regression algorithms to determine the credit score of an individual by considering 14 different factors : 

### 1. Age (Integer) : A value between 18-70 years with biasing towards younger candidates.

### 2. Gender (String) : Male or Female with slight biasing towards females.

### 3. Dependents (Integer) : Number of dependents (spouse/children/family) on the applicant between 1 to 5. Applicants with lesser number of dependents get a bonus whereas applicants with more number of dependents are penalized.

### 4. Education (String) : Under-Graduate, Graduate or Masters degree. A higher degree gets a bonus score.

### 5. Employment Duration (Integer) : Value between 0 to 40 months. Bonus score towards applicants having higher duration and penalty for lower duration.

### 6. Existing_Credit_History (Integer) : A score of previous credit history (if existing) between 0 to 800. It is 0 for a fresh applicant. Lower score is penalized whereas a higher score receives a bonus.

### 7. Basic_Fraud_Threat (String) : Expectation of an applicant to do a fraud (High, Medium, Low). Derived from Reference Credit Score and Delinquent Payment. Harsh penalty for High threat.

### 8. Annual Income (Integer) : Value between 2.4 lakhs to 24 lakhs. Bonus score towards applicants having high income and penalty for applicants having lower income.

### 9. Reference_Credit_Score (Integer) : Value between 0 to 800. 0 for applicants with no references. High credit score leads to a bonus whereas low credit score leads to a small penalty.

### 10. Proof of Identity (String) : Whether an applicant showed his proof of identity or not (Y or N). Penalzied applicants who didn't show proof of identity.

### 11. Delinquent_Payment (Integer) : Number of overdues/fines on an applicant (0 to 5). Bonus score for lower number of delinquent payments and penalty for higher number of delinquent payments.

### 12. Current_Residence_Duration (Integer) : Duration of an applicant's current residence between 0 to 5 years. Bonus score for higher duration and penalty for lower duration.

### 13. Foreign_Worker (String) : Whether an applicant is a foreign worker or not (Y or N). Penalty for being a foreign worker.

### 14. Known Debt (String) : Known debt level on an applicant (High, Medium, Low). Penalty for high level and bonus score for lower level.


## I intend on updating this in the future to incorporate things to make this seem more realistic
