# Loan-Portfolio-Analysis
I carried out risk analysis for Daiz Bank by analyzing its loan portfolio. This repository contains the dataset, reports, and recommendations given after my analysis.

## Project Rationale
Risk analysis refers to the assessment process that identifies the potential for any adverse events that may negatively affect Daiz Bank in the process of giving out a loan. Conducting a risk analysis can help the bank determine whether they should approve a loan or financial application, and what actions they may need to take to protect their interests. This type of analysis facilitates a balance between risks and risk reduction.

Risk analytics provides the tools and methodologies to analyze vast datasets, identify hidden patterns, and extract actionable insights in real-time. Unlike traditional methods that rely on historical data, risk analytics offers the advantage of adaptability. It can continuously process incoming data, enabling the bank to respond promptly to shifting market dynamics, economic indicators, and emerging risks. By harnessing the predictive power of analytics, the bank can proactively identify potential trouble spots within the portfolio, enabling timely interventions that mitigate losses and uphold the institution’s financial health.

Risk analytics enables the bank to differentiate between high and low-risk clients and tailor its lending strategies accordingly. For clients, this means fairer loan terms, while for the bank, it translates into a more diversified portfolio. In essence, it allows the bank to strike a balance between profitability and risk exposure, ensuring long-term financial sustainability.

Lastly, risk analytics isn’t just about managing risk; it’s also about optimizing opportunities. By delving deep into the data, Daiz Bank can identify underserved markets, customer segments with growth potential, and innovative lending products. This proactive approach doesn’t just shield the bank from potential losses; it propels it forward into a future where data isn’t just a tool for risk mitigation, but a catalyst for growth.

## Aim of the Project
This project carries a lofty mission: to revolutionize the bank’s approach to loan portfolio risk assessment. Our endeavor is rooted in the belief that data analytics, powered by advanced tools like Power BI, holds the key to unlocking unparalleled insights. These insights will not only empower the bank to make more informed lending decisions but also optimize its risk management strategies.

The bank’s aim is not merely profitability, but the creation of a resilient and diversified portfolio that thrives in the face of uncertainty, reduces credit losses, ensures compliance with ever-evolving regulations, and, more importantly, propels the bank forward into a future where data isn’t just a tool for risk mitigation, but a catalyst for growth and innovation.

## Data Description
*Note: A default on a loan occurs when payments are missed for a specified period, and it has been established that the loan is no longer going to be repaid. Arrears are payments that are late, delayed, or missed, but where the borrower has every intention of making the payments later.*

**The bank has a database with 1500 rows of expense information for analysis, with the following attributes:**

1. `Loan ID`: A unique identifier for each loan in the portfolio.
2. `Borrower ID`: A unique identifier for each borrower associated with the loan.
3. `Borrower Name`: The full name of the borrower.
4. `Gender`: The gender of the borrower.
5. `Borrower Age`: The age of the borrower.
6. `Marital Status`: The marital status of the borrower.
7. `Borrower Address`: The address of the borrower.
8. `Borrower Email`: The email address of the borrower.
9. `Borrower Phone Number`: The phone number of the borrower.
10. `Loan Amount`: The amount of money borrowed by the borrower.
11. `Loan Type`: The type of loan, such as personal loan, mortgage, auto loan, or commercial loan.
12. `Interest Rate`: The annual interest rate charged on the loan.
13. `Loan Term`: The duration of the loan, in years.
14. `Loan Status`: The status of the loan, such as “Paid Off,” “Defaulted,” or “In Arrears.”
15. `Credit Score`: The credit score of the borrower, which reflects their creditworthiness.
16. `Income`: The income of the borrower.
17. `Employment Status`: The employment status of the borrower, such as “Employed,” “Self-Employed,” or “Unemployed.”
18. `Loan Origination Date`: The date when the loan was initially issued.
19. `Loan Paid Date`: The date when the loan was paid off or settled.

The data was transformed using Power Query. I created the `Date Table` and also defined custom columns to make the analysis easier. I also standardized the data types and formats. I then head over to Power BI to create a relationship between the `Date Table` and `Loan Origination Date` in the `Loan dataset`.

## Dashboard Design


<img width="1100" height="718" alt="image" src="https://github.com/user-attachments/assets/982958e9-a15a-4e77-88af-bbf55a91d31c" />

---
<img width="1100" height="721" alt="image" src="https://github.com/user-attachments/assets/037f86b5-db8d-451f-8fff-1a7fddae9575" />

---
<img width="1100" height="720" alt="image" src="https://github.com/user-attachments/assets/544eba15-0094-4aee-8159-2f0e67af19b0" />


## Insights
1. From July 2018 to September 2021, the total amount of loans given out was $36.6 million. These loans generated a total of $1.8 million in interest.
2. Year 2018 has an Annual Portfolio yield of 5.13%, 2019 has 4.78%, 2020 has 5.14%, while 2021 has 5.10%.
3. The KPIs show the Total Approved loans over the 4-year period, the number of male and female borrowers, the average income of the borrowers, and the average credit score.
4. The Quarter with the highest number of loan volume is the 3rd quarter of 2019, followed closely by the 4th quarter of 2018. The least loan volume can be seen in the 3rd quarter of 2018.
5. People between the Age range of 35–41 collected the highest amount of loans; $9.7 million. This age group comprises men and women who have multiple needs they cater to and are most time self-dependent.
6. Married folks are also known to incur a lot of expenses and responsibilities. From our analysis, we see that they collected a loan amount of $22.9 million for single folks ,with $13.6 million.
7. Employed folks also collected the most loans. Because of their employment status, they have a high chance of getting a loan due to
their creditworthiness and income status.
8. January 2021 recorded the peak of loan transactions. It is believed that the aftermath of the COVID-19 lockdown puts many people at the mercy of loans in order to get back on their feet.
9. More KPIs are shown on the Loan status and type analysis. They are the Loan types, the loan status, and how they affect the overall portfolio.
10. A total of $6.5 million worth of loans are still in default. People who have a high credit score and a  high income are the highest defaulters.

## Recommendations
1. Adjust interest rates and terms based on the risk profile of borrowers. Higher-risk borrowers should have higher interest rates to compensate for potential default.
2. Increase the frequency of monitoring for high borrowers to identify potential issues early.
3. Require collateral for high-borrower loans to provide a buffer in case of default.
4. Develop strategies for loan renegotiation for borrowers showing signs of distress to avoid outright defaults.
5. Offer financial literacy programs for borrowers to improve their financial management and reduce the likelihood of default.
6. Implement or refine credit scoring models to better assess borrower risk and adjust lending criteria accordingly.
7. Stay informed about macroeconomic conditions and adjust lending strategies in response to economic indicators that could affect borrower performance.

## Conclusion
The ability to continuously monitor and analyze your loan portfolio empowers you to make informed decisions based on evidence rather than intuition. By leveraging data analysis, you can:

1. Identify opportunities: Uncover hidden patterns and trends that can lead to new business opportunities or risk mitigation strategies.
2. Optimize resource allocation: Allocate resources effectively by understanding which segments or products drive the most value.
3. Mitigate risks: Proactively identify potential issues and take corrective actions before they escalate.
4. Enhance efficiency: Streamline processes and improve operational efficiency by automating reporting and analysis.
5. Improve profitability: Drive revenue growth and reduce costs by optimizing pricing, underwriting, and collections strategies.
