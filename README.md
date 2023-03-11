# (Dataset Exploration Title)
## by David Apine Kwenev


## Dataset

The [dataset](https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv%26amp;sa%3DD%26amp;ust%3D1581581520570000&sa=D&source=editors&ust=1678221709762763&usg=AOvVaw2b_sgw5A_aYBCO_k05-0Pi) contains 113,937 loans with 81 features for each loan. The [data dictionary](https://www.google.com/url?q=https://docs.google.com/spreadsheet/ccc?key%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&source=editors&ust=1678221709763697&usg=AOvVaw1OQTd8dKmyZ1zfhIVnVwvJ) explains the features in the data set. The project objective is not expected to explore all of the variables but the focus is to explore about 10 to 15 of them.


## Summary of Findings

During the exploration of the dataset, the following insights were drawn:

- About 54% of borrowers are home owners, while 56% of them are not home owners.
- The Income range '50,000-74,999' dollars is predominant with about 23000 records (after null rows have been dropped of course), followed by the '25,000-49,999' dollar income range.
- The '1-24,999' dollars income range has the least records with less than 5000.
- The state of California recorded the highest number of borrowers with 12% followed by New York and Texas, while Wyoming has the least.
- About 86% of borrowers are employed while the remaining 14% is spread across Full-time, Retired, Part-time, Self-employed, Not employed, and Other.
- About 63% of the listing categories are Debt Consolidation while less than 10% are for Business
- Loans with "AA" ProsperRating_Alpha category has lesser count while those with "C" category has the highest count of about 21%
- More than 67% of the LoanStatus is Current and about 23% Completed
- About 15.0% of the borrowers are with a rating score of 8.0 which happened to be the highest, followed by 6.0 and 4.0 with 14.6% and 14.2% respectively
- Majority of the borrowers salary ranges between 2500 to 7500 USD with the peak at 5000 USD.
- Majority of the borrowers have their Employment status duration less than 200.
- Majority of the loans are funded by 100 investors and below.
- The original loan amount tends to peak at 5000 USD, 10000 USD, and 15000 USD
- LoanOriginalAmount is heavily positively correlated with MonthlyLoanPayment as one would expect.
- On average, the Loan Amount tend to increase with higher income ranges.
- Home owners consistently have higher Loan Amount across all Income Ranges.

Some of these findings will be taken to the explanatory notebook to expantiate more on them.


## Key Insights for Presentation

For the presentation, the following insights will be presented:

- It was found that 31% of borrowers earn between 50000 to 75000 dollars while 28% earn between 25000 to 50000 US dollars.
- Borrowers that fall within these two Income Ranges constitute more than 50% of the entire dataset.
- 37% of the borrowers come from 5 states namely (in decreasing order of pupolarity); California, New York, Texas, Florida, and Illinois with California taking the lead with about 13% borrowers.
- 64% of the borrowers listed **Debt Consolidation** as their reason for taking the loan. Only about 5% of them mentioned **Business** as reason for the loan.
- Being a home owner as well as having a high income plays a very big role on the Loan Amount.