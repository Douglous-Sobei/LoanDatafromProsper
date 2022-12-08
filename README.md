# LoanDatafromProsper
**PROJECT : LOAD THE DATA FROM PROSPER**
**Project on Loan Data from Prosper Dataset**

> This data set contains about 113,937 records of loans with 81 variables on each loan, including loan amount, borrower rate, current loan status, borrower income, and so on

**Summary of Findings**

> During investing the ProsperRating (Alpha) and the ProsperScore as it relates to the BorrowerRate I could know an explanation for why the ProsperScore wasn't as highly correlated to the BorrowerRate. It is opposite the other credit risk features must use different criteria in coming up with its value

> A surprising interaction is that the borrower's APR and loan amount has a negative correlation when the Prosper ratings are from HR to B, but the correlation is turned to be positive when the ratings are A and AA. Another interesting thing is that the borrower APR decreases with the increase of borrow term for people with HR-C ratings. But for people with B-AA ratings, the borrower's APR increase with the borrowing term.

> BorrowerRate increases for longer Term loans when split up by ProsperRating (Alpha). The opposite relationship would be expected as longer-term loans generally carry a lower risk profile and have a longer time to accrue interest

> In exploring how the interest rate of a loan is affected by the loans Term (length of loan) I discovered that under every ProsperRating short term loans had a lower interest rate. Unsurprisingly those with a higher/better ProsperRating had a lower interest rate.

__Key Insights for Presentation__

> I focused on features that would affect the borrower's APR, which key plots with a high data-to-ink ratio for the presentation. The plots I've chosen shows the distribution of main variables, Loan status, monthly income, Prosper rating and I've tried to tell a story about what are major predictors for loan status and Prosper rating variables. wI started by showing the distribution of borrower APR and loan amount variables. Then, I showed the relationship between's APR vs. loan amount, as well as between's APR APR vs. rating. I also investigated the effect of rating on the relationship between APR and loan amount, as well as the effect of rating on the relationship between borrower APR and term.



__Limitations__

> Exploratory Data Analysis is a good way to know the data using vivid and interesting visualizations. However, to make a final statement about the relationships among variables we need to conduct the statistical tests and build predictive models.

**References**

* https://video.udacity-data.com/topher/2021/September/6155a85c_example-project/example-project.zip
* https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv&sa=D&ust=1554482573645000

