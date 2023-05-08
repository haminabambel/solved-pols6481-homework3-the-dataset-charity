Download Link: https://assignmentchef.com/product/solved-pols6481-homework3-the-dataset-charity
<br>
The dataset <em>charity.dta</em> describes 4,266 survey respondents’ charitable giving behavior. The dependent variable (<strong><em>gift</em></strong> ) is donations, measured in Dutch guilders. The explanatory variables are the number of mailings the individual received in the past year (<strong><em>mailsyear</em></strong> ), the average of past gifts by the individual (<strong><em>avggift</em></strong> ), and the proportion of mailings to which the individual responded in the past (<strong><em>propresp</em></strong> ).

<ol>

 <li>Estimate the following bivariate regression model using ordinary least squares:</li>

</ol>

<ul>

 <li>Interpret the coefficient. For example, you can complete the sentence, for every additional mailing that the respondent received, s/he donated ____ (more? less?) guilder.</li>

 <li>Can be statistically distinguished from <u>one</u>? (Test the null hypothesis H<sub>0</sub>: β<sub>1</sub> = 1)</li>

 <li>Suppose each mailing costs 1 guilder to produce and send, so that the charity is interested in whether it can expect a <em>net</em> gain on mailings. Can can be statistically distinguished from 1? (Test the null hypothesis is H<sub>0</sub>: β<sub>1</sub> = 1.)</li>

</ul>

<ol start="2">

 <li>Estimate the following multivariate regression model using ordinary least squares:</li>

</ol>

<ul>

 <li>How does the estimated slope coefficient from the multivariate model compare with the estimated slope coefficient  from the simple regression model?</li>

 <li>How do the standard error of the regression (i.e., Root MSE) and the standard error of from the multivariate model compare to the corresponding statistics in the bivariate model?</li>

 <li>Can be statistically distinguished from <u>one</u>? (Test the null hypothesis is H<sub>0</sub>: β<sub>1</sub> = 1)</li>

 <li>Perform an F test of the hypothesis that <strong><em>avggift</em></strong> and <strong><em>propresp</em></strong>  have no significant effect (i.e., H<sub>0</sub>: β<sub>1</sub> = 0, β<sub>2</sub> = 0) on <strong><em>gift</em></strong> . Perform the R<sup>2</sup> version by hand and identify the F critical value. Repeat the test using R Studio to verify your conclusions about the joint significance of these variables.</li>

</ul>

<ol start="3">

 <li>Now turn your attention to heteroscedasticity. Unfortunately the dataset does not include data on income, but we can treat two variables – <strong><em>avggift</em></strong> and <strong><em>propresp</em></strong>  – as proxies for income, under the theory that wealthier people are able to be more generous.</li>

</ol>

<ul>

 <li>Plot the residuals against each regressor and against the fitted value; include figures in what you turn in. Are you concerned about heteroscedasticity?</li>

 <li>Perform an appropriate test for diagnosing heteroscedasticity and report your findings.</li>

 <li>Re-estimate the model in 2. using Feasible Generalized Least Squares. Show your results. Report the effects of this re-estimation on coefficients, standard errors, and <em>t</em> Point out any noteworthy changes from the model estimated using Ordinary Least Squares.</li>

</ul>

<ol start="4">

 <li>Re-estimate the variances of the coefficients to obtain <u>robust</u> <u>standard</u> <u>errors</u>. Report them and the new <em>t</em> statistics. Are there any noteworthy changes to your conclusions, compared to OLS?</li>

</ol>

The file <em>beauty.dta</em> contains data used in Wooldridge’s example, “Effects of Physical Attractiveness on Wage.”

The dataset has 1,260 observations, of whom 436 were women and 824 were men. These data are from Daniel Hamermesh and Jeff Biddle (1994) “Beauty and the Labor Market,” <em>American Economic Review </em>84: 1174–94.

The example’s focus is whether wages are systematically related to an employee’s attractiveness. The dependent variable is <strong><em>wage</em></strong>. The key explanatory variable is <strong><em>looks</em></strong>, which is an ordinal scale with five ranks: homely (1), quite plain (2), average (3), good looking (4), and strikingly beautiful/handsome (5). Your control variables are the employee’s education (<strong><em>educ</em></strong>), experience (<strong><em>exper</em></strong>), and gender (<strong><em>female</em></strong>)

<ol start="5">

 <li>Estimate the following simple regression model using ordinary least squares:</li>

</ol>

<ul>

 <li>What does the regression coefficient tell us about the relationship between attractiveness and wages?</li>

 <li>Is the estimated coefficient statistically significant?</li>

 <li>How much of the variance in wages did the simple regression model explain?</li>

</ul>

<ol start="6">

 <li>Estimate the following multiple regression model using ordinary least squares:</li>

</ol>

<ul>

 <li>How are the coefficient and its standard error different from  and its standard error? Why?</li>

 <li>Which estimated coefficients are statistically significant? Interpret their effects in terms of how a one-unit increase in each variable (one rank higher in attractiveness, one year of education, or one year of experience) effects hourly wages.</li>

 <li>How much of the variance in wages does a model with these three variables explain?</li>

</ul>

<ol start="7">

 <li>The data come from the 1977 Quality of Employment Survey. It is plausible that there was a gender gap in wages, therefore estimate the following model, which adds a fourth variable for gender.</li>

</ol>

<ul>

 <li>Is this new coefficient statistically significant? Interpret its effect.</li>

 <li>How did each coefficient and each standard error change between the three-variable and four-variable model?</li>

 <li>How much of the variance in wages does a model with these four variables explain?</li>

 <li>How would you use an F test to decide which variables to keep and which to drop? Fill in the table on the next page and perform F tests making the following comparisons:

  <ol start="5">

   <li>Multiple regression in 5. null model</li>

  </ol></li>

</ul>

Change in R<sup>2</sup>: <u>                             </u>     F statistic: <u>                                     </u>     F* critical value: <u>                         </u>

<ol start="6">

 <li>Multiple regression in 6. null model</li>

</ol>

Change in R<sup>2</sup>: <u>                             </u>     F statistic: <u>                                     </u>     F* critical value: <u>                         </u>

<ol start="6">

 <li>Multiple regression in 6. vs. multiple regression in 5.</li>

</ol>

Change in R<sup>2</sup>: <u>                             </u>     F statistic: <u>                                     </u>     F* critical value: <u>                         </u>

<ol start="6">

 <li>Multiple regression in 7 vs. multiple regression in 6.</li>

</ol>

Change in R<sup>2</sup>: <u>                             </u>     F statistic: <u>                                     </u>     F* critical value: <u>                         </u>




<table width="576">

 <tbody>

  <tr>

   <td width="144">Model:Variables:</td>

   <td width="106">Nullnone</td>

   <td width="106">Simple<em>looks</em></td>

   <td width="115">Multiple<em>looks</em>,<em>educ</em>,<em>exper</em></td>

   <td width="106">Multiple<em>looks</em>,<em>educ</em>,<em>exper</em>,<em>female</em></td>

  </tr>

  <tr>

   <td width="144">model df used </td>

   <td width="106"> </td>

   <td width="106"> </td>

   <td width="115"> </td>

   <td width="106"> </td>

  </tr>

  <tr>

   <td width="144">residual df remaining </td>

   <td width="106"> </td>

   <td width="106"> </td>

   <td width="115"> </td>

   <td width="106"> </td>

  </tr>

  <tr>

   <td width="144">total sum of squares </td>

   <td width="106"> </td>

   <td width="106"> </td>

   <td width="115"> </td>

   <td width="106"> </td>

  </tr>

  <tr>

   <td width="144">residual sum of squares</td>

   <td width="106"> </td>

   <td width="106"> </td>

   <td width="115"> </td>

   <td width="106"> </td>

  </tr>

  <tr>

   <td width="144">model R<sup>2</sup> </td>

   <td width="106"> </td>

   <td width="106"> </td>

   <td width="115"> </td>

   <td width="106"> </td>

  </tr>

 </tbody>

</table>

7½. Before moving on to the final question, perform a simple comparison of average wages for male and female employees. (Do not use the multivariate model, just use a bivariate model with a dummy variable for gender, or carry out a difference-of-means test using the techniques from last semester.)

<ul>

 <li>What is the <em>t</em> statistic?</li>

 <li>What is the <em>F</em> statistic for an analysis of variance with two groups (male, female)?</li>

 <li>How does this <em>F</em> statistic compare to the final <em>F</em> statistic (#d. under the last bullet point) that you computed for problem 7? Why is it not identical?</li>

</ul>

<ol start="8">

 <li>Now turn your attention to potential heteroscedasticity, i.e., non-constant error variance.</li>

</ol>

<ul>

 <li>Examine the data using scatterplots, plotting the residuals against the regressors and/or the fitted values; do you see any reason to be concerned about heteroskedasticity? (Include at least one figure in what you submit.)</li>

 <li>Perform an appropriate test for diagnosing heteroskedasticity. Write a paragraph describing how the test works and report your findings using this test.</li>

 <li>Re-estimate the model in 7. using Feasible Generalized Least Squares. Show your results. Point out any noteworthy changes in coefficients, standard errors, and <em>t</em> statistics, compared to a model estimated using Ordinary Least Squares.</li>

 <li>Re-estimate the variances of the coefficients from the model in 7. to obtain robust standard errors. Show your results. Point out any noteworthy changes in standard errors, and <em>t</em> statistics, compared to a model estimated using Ordinary Least Squares.</li>

</ul>


