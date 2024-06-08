OBJECTIVE:
Gain an understanding of Principal Component Analysis

Internet Buzz and the Movie Box Office:


In his undergraduate honors thesis, Versaci (2009) investigated what he termed “internet buzz variables” to see whether they provide any additional predictive information towards a movie's box office revenues (beyond movie characteristics like genre, actors, budget, etc.). boxOffice.csv contains this data involving 62 movies (all wide-released movies between November 7, 2008 and April 3, 2009); the variables available (along with their descriptions) are in the table below. We will conduct the analysis ignoring the “buzz” variables (addict, cmngsoon, fandango, and cntwait3) first.


HERE I AM TRYING TO SOLVE THE FOLLOWING QUESTIONS:


1. Plot histograms of the continuous variables (box, budget, starpwr) to see if any transformations are needed. Are any of them skewed? Apply a log-transformation to all the skewed variables.
2. Run a linear regression of box office revenues on the “traditional” variables (i.e., using all the independent variables (except the “buzz” variables). If any variables were transformed, be sure to use the transformed versions of those variables. What are the R2 and adjusted- R2 values? Which variables (if any) are significant at the 0.10 level, based on the t-statistics and associated probabilities (p > |t|)?
3. Run another linear regression using only the variables that were significant (again, ignoring the “buzz” variables). What are the R2 and adjusted- R2 values? Are all the variables still significant at the 0.10 level?
4. Plot histograms of the four “buzz” variables. Are any of them skewed? Apply a log-transformation to all the skewed variables.
5. Run a linear regression of box office revenues on all the independent variables, including the “buzz” variables (transformed as needed). What are the R2 and adjusted- R2 values? Which variables (if any) are significant at the 0.10 level, based on the t-statistics and associated probabilities (p > |t|)?
6. Run another linear regression using only the variables that were significant. What are the R2 and adjusted- R2 values? Are all the variables still significant at the 0.10 level?
7. Compare the models developed so far – which of these would you choose, and why?
8. Apply Principal Component Analysis to just the 4 “buzz” variables. If you transformed any of them, make sure you use the transformed versions. Also make sure that you standardize the variables first. What are the eigen values associated with each component? How many principal components are selected using (i) Kaiser's Rule, and using “explained variance" thresholds of (ii) 60%, (iii) 70%, (iv) 80% and (v) 90%?
9. Run a linear regression using all the “traditional” independent variables (if transformed, use the transformed versions) and all 4 principal components (the only variables you should not use here are the four “buzz” variables). What are the R2 and adjusted- R2 values? Which variables (if any) are significant at the 0.10 level? In particular, are any of the principal components significant? What can you say about this model vis-à-vis the other models built so far?
10. Now run regressions using the number of principal components based on (i) Kaiser's Rule and “explained variance” thresholds of (ii) 60%, (iii) 70%, (iv) 80% and (v) 90% (if any of the models are identical, point this out and run it only once). Compare all the regression models involving the principal components (including the one involving all four components). Which of these would you recommend, and why?
11. Now apply Principal Component Analysis to the 4 “buzz” variables and the other continuous variables (budget and starpowr). Again, use transformed versions of the variables if any were transformed and standardize the variables first. What are the eigen values associated with each component? How many principal components are selected using (i) Kaiser's Rule, and using “explained variance" thresholds of (ii) 60%, (iii) 70%, (iv) 80% and (v) 90%?
12. Next, run regressions using the number of principal components based on (i) Kaiser's Rule and “explained variance” thresholds of (ii) 60%, (iii) 70%, (iv) 80% and (v) 90%. Compare these regression models and explain which one you would recommend, and why?
