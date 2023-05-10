# Cronbach-s-Alpha-Test-for-Internal-Consistency-DEI-Survey-Results
Collaborator @JulianGendreau —> https://github.com/JulianGendreau
Call:
glm(formula = Eight ~ PostFellowshipTraining + Fellowship + Residency + 
    MedicalSchool)

Deviance Residuals: 
     Min        1Q    Median        3Q       Max  
-2.06349  -0.17647  -0.06349   0.82353   1.00000  

Coefficients: (1 not defined because of singularities)
                       Estimate Std. Error t value Pr(>|t|)    
(Intercept)             4.06349    0.09887  41.100  < 2e-16 ***
PostFellowshipTraining  0.11298    0.16699   0.677  0.49999    
Fellowship             -1.06349    0.36461  -2.917  0.00422 ** 
Residency               0.02346    0.19118   0.123  0.90252    
MedicalSchool                NA         NA      NA       NA    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.6158124)

    Null deviance: 80.608  on 124  degrees of freedom
Residual deviance: 74.513  on 121  degrees of freedom
AIC: 300.07

Number of Fisher Scoring iterations: 2



glm(formula = Ten ~ PostFellowshipTraining + Fellowship + Residency + 
    MedicalSchool)

Deviance Residuals: 
     Min        1Q    Median        3Q       Max  
-2.74603  -0.74603   0.04348   0.85294   1.25397  

Coefficients: (1 not defined because of singularities)
                       Estimate Std. Error t value Pr(>|t|)    
(Intercept)              3.7460     0.1145  32.713   <2e-16 ***
PostFellowshipTraining   0.4010     0.1934   2.073   0.0403 *  
Fellowship              -0.5460     0.4223  -1.293   0.1985    
Residency                0.2105     0.2214   0.951   0.3437    
MedicalSchool                NA         NA      NA       NA    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.826097)

    Null deviance: 105.952  on 124  degrees of freedom
Residual deviance:  99.958  on 121  degrees of freedom
AIC: 336.79

Number of Fisher Scoring iterations: 2

> wit <- glm(formula = Eleven ~ PostFellowshipTraining + Fellowship + Residency + MedicalSchool)
> summary(wit)

Call:
glm(formula = Eleven ~ PostFellowshipTraining + Fellowship + 
    Residency + MedicalSchool)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-2.6349  -0.6349   0.1304   0.3651   1.3651  

Coefficients: (1 not defined because of singularities)
                       Estimate Std. Error t value Pr(>|t|)    
(Intercept)              3.6349     0.1153  31.519   <2e-16 ***
PostFellowshipTraining   0.3945     0.1948   2.025    0.045 *  
Fellowship              -0.2349     0.4253  -0.552    0.582    
Residency                0.2346     0.2230   1.052    0.295    
MedicalSchool                NA         NA      NA       NA    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.8378716)

    Null deviance: 105.73  on 124  degrees of freedom
Residual deviance: 101.38  on 121  degrees of freedom
AIC: 338.56

Number of Fisher Scoring iterations: 2


> wit <- glm(formula = Fifteen ~ PostFellowshipTraining + Fellowship + Residency + MedicalSchool)
> summary(wit)

Call:
glm(formula = Fifteen ~ PostFellowshipTraining + Fellowship + 
    Residency + MedicalSchool)

Deviance Residuals: 
     Min        1Q    Median        3Q       Max  
-1.91304  -0.69841   0.08696   0.30159   1.30159  

Coefficients: (1 not defined because of singularities)
                       Estimate Std. Error t value Pr(>|t|)    
(Intercept)              3.6984     0.1031  35.872   <2e-16 ***
PostFellowshipTraining   0.3898     0.1741   2.239    0.027 *  
Fellowship              -0.2984     0.3802  -0.785    0.434    
Residency                0.2146     0.1994   1.077    0.284    
MedicalSchool                NA         NA      NA       NA    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.6696795)

    Null deviance: 85.472  on 124  degrees of freedom
Residual deviance: 81.031  on 121  degrees of freedom
AIC: 310.55

Number of Fisher Scoring iterations: 2







Call:
glm(formula = Three ~ Lecture + Interactive + Rolemodel + Informal + 
    Simulated)

Deviance Residuals: 
     Min        1Q    Median        3Q       Max  
-2.01515  -0.53846  -0.01515   0.98485   1.46154  

Coefficients: (1 not defined because of singularities)
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   3.5385     0.2591  13.654   <2e-16 ***
Lecture       0.4767     0.2835   1.681   0.0954 .  
Interactive   0.4615     0.3154   1.463   0.1461    
Rolemodel     1.4615     0.5985   2.442   0.0161 *  
Informal      0.1888     0.3828   0.493   0.6228    
Simulated         NA         NA      NA       NA    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.8730212)

    Null deviance: 106.79  on 119  degrees of freedom
Residual deviance: 100.40  on 115  degrees of freedom
AIC: 331.14

Number of Fisher Scoring iterations: 2







> wit <- glm(formula = Six ~ Lecture + Interactive + Rolemodel + Informal + Simulated)
> summary(wit)

Call:
glm(formula = Six ~ Lecture + Interactive + Rolemodel + Informal + 
    Simulated)

Deviance Residuals: 
     Min        1Q    Median        3Q       Max  
-2.33333  -0.33333   0.04545   0.66667   1.38462  

Coefficients: (1 not defined because of singularities)
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  3.61538    0.22367  16.164  < 2e-16 ***
Lecture      0.33916    0.24470   1.386  0.16843    
Interactive  0.71795    0.27224   2.637  0.00951 ** 
Rolemodel    0.05128    0.51653   0.099  0.92109    
Informal    -0.34266    0.33038  -1.037  0.30183    
Simulated         NA         NA      NA       NA    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.6503395)

    Null deviance: 85.467  on 119  degrees of freedom
Residual deviance: 74.789  on 115  degrees of freedom
AIC: 295.81

Number of Fisher Scoring iterations: 2



Call:
glm(formula = Seven ~ Lecture + Interactive + Rolemodel + Informal + 
    Simulated)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-1.8636  -0.3333   0.1364   0.6667   1.5385  

Coefficients: (1 not defined because of singularities)
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   3.4615     0.2379  14.548  < 2e-16 ***
Lecture       0.4021     0.2603   1.545  0.12518    
Interactive   0.8718     0.2896   3.010  0.00321 ** 
Rolemodel     0.5385     0.5495   0.980  0.32919    
Informal     -0.2797     0.3515  -0.796  0.42774    
Simulated         NA         NA      NA       NA    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.7359988)

    Null deviance: 97.867  on 119  degrees of freedom
Residual deviance: 84.640  on 115  degrees of freedom
AIC: 310.65

Number of Fisher Scoring iterations: 2



> wit <- glm(formula = Twelve ~ Lecture + Interactive + Rolemodel + Informal + Simulated)
> summary(wit)

Call:
glm(formula = Twelve ~ Lecture + Interactive + Rolemodel + Informal + 
    Simulated)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-2.3846  -0.7879   0.2121   0.6364   1.6154  

Coefficients: (1 not defined because of singularities)
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  3.38462    0.25756  13.141   <2e-16 ***
Lecture      0.40326    0.28178   1.431   0.1551    
Interactive  0.68946    0.31349   2.199   0.0299 *  
Rolemodel    0.28205    0.59480   0.474   0.6363    
Informal    -0.02098    0.38044  -0.055   0.9561    
Simulated         NA         NA      NA       NA    
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.8623583)

    Null deviance: 105.467  on 119  degrees of freedom
Residual deviance:  99.171  on 115  degrees of freedom
AIC: 329.67

Number of Fisher Scoring iterations: 2





Call:
glm(formula = Twenty ~ UNDERREPRESENTED)

Odds Ratios:
                     or or.lci or.uci  Pr(>|z|)    
(Intercept)      21.267 16.658 27.150 < 2.2e-16 ***
UNDERREPRESENTED  1.589  1.088  2.319    0.0181 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -7.365     Nagelkerke R2: 0.049

> CronbachAlpha(Chron)
[1] 0.911193



> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Seventeen ~ Sex)

Odds Ratios:
                   or or.lci  or.uci  Pr(>|z|)    
(Intercept)   100.776 73.975 137.288 < 2.2e-16 ***
Sex1            0.672  0.469   0.963    0.0325 *  
SexNot listed   0.542  0.094   3.114    0.4935    
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -14.348     Nagelkerke R2: 0.043



> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Nineteen ~ Sex)

Odds Ratios:
                  or or.lci or.uci  Pr(>|z|)    
(Intercept)   68.430 49.071 95.425 < 2.2e-16 ***
Sex1           0.614  0.417  0.904    0.0150 *  
SexNot listed  0.294  0.045  1.926    0.2041    
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -11.08     Nagelkerke R2: 0.06



> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Twentytwo ~ Sex)

Odds Ratios:
                  or or.lci or.uci  Pr(>|z|)    
(Intercept)   35.897 25.132 51.272 < 2.2e-16 ***
Sex1           0.606  0.400  0.917    0.0195 *  
SexNot listed  0.076  0.010  0.569    0.0135 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -7.083     Nagelkerke R2: 0.086



> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Three ~ `IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`)

Odds Ratios:
                                                        or or.lci  or.uci  Pr(>|z|)    
(Intercept)                                         80.551 52.330 123.992 < 2.2e-16 ***
`IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`  0.603  0.377   0.962    0.0359 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -11.743     Nagelkerke R2: 0.039



> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Six ~ `IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`)

Odds Ratios:
                                                        or or.lci  or.uci  Pr(>|z|)    
(Intercept)                                         85.153 58.220 124.545 < 2.2e-16 ***
`IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`  0.548  0.363   0.828    0.0050 ** 
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -11.584     Nagelkerke R2: 0.071


> wit <- glm(formula = Twelve~ `IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`)
> summary(wit)

Call:
glm(formula = Twelve ~ `IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-2.6863  -0.6863   0.3137   0.3137   1.3137  

Coefficients:
                                                    Estimate Std. Error t value Pr(>|t|)    
(Intercept)                                           4.2222     0.2181  19.355   <2e-16 ***
`IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`  -0.5359     0.2366  -2.265   0.0253 *  
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.8565415)

    Null deviance: 105.47  on 119  degrees of freedom
Residual deviance: 101.07  on 118  degrees of freedom
AIC: 325.95

Number of Fisher Scoring iterations: 2



> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Thirteen ~ `IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`)

Odds Ratios:
                                                        or or.lci  or.uci  Pr(>|z|)    
(Intercept)                                         85.153 54.899 132.078 < 2.2e-16 ***
`IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`  0.437  0.272   0.704  9.09e-04 ***
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -10.346     Nagelkerke R2: 0.095

Call:
glm(formula = Fourteen ~ `IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-2.7059  -0.7059   0.2941   0.2941   1.2941  

Coefficients:
                                                    Estimate Std. Error t value Pr(>|t|)    
(Intercept)                                           4.3889     0.1860  23.601  < 2e-16 ***
`IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`  -0.6830     0.2017  -3.386 0.000963 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.6224936)

    Null deviance: 80.592  on 119  degrees of freedom
Residual deviance: 73.454  on 118  degrees of freedom
AIC: 287.65

Number of Fisher Scoring iterations: 2



> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Fifteen ~ `IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`)

Odds Ratios:
                                                        or or.lci  or.uci  Pr(>|z|)    
(Intercept)                                         85.153 58.731 123.460 < 2.2e-16 ***
`IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`  0.492  0.329   0.736  7.79e-04 ***
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -10.981     Nagelkerke R2: 0.1


> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Sixteen ~ `IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`)

Odds Ratios:
                                                        or or.lci  or.uci  Pr(>|z|)    
(Intercept)                                         72.080 47.810 108.670 < 2.2e-16 ***
`IN WHAT AREA OF THE UNITED STATES DO YOU PRACTICE`  0.559  0.358   0.872    0.0117 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -10.573     Nagelkerke R2: 0.057




> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Ten ~ Rural)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 51.986 43.512 62.111 < 2.2e-16 ***
Rural        0.603  0.381  0.954    0.0327 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -11.173     Nagelkerke R2: 0.041


> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Fourteen ~ Rural)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 48.065 41.058 56.267 < 2.2e-16 ***
Rural        0.652  0.434  0.979    0.0414 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -10.718     Nagelkerke R2: 0.038


> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Nineteen ~ Rural)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 50.977 42.377 61.322 < 2.2e-16 ***
Rural        0.615  0.381  0.990    0.0477 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -11.059     Nagelkerke R2: 0.035


> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Twenty ~ Rural)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 28.032 22.870 34.359 < 2.2e-16 ***
Rural        0.574  0.339  0.970    0.0404 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -7.352     Nagelkerke R2: 0.037


> wit <- glm(formula = Twentyone~ Rural)
> summary(wit)

Call:
glm(formula = Twentyone ~ Rural)

Deviance Residuals: 
    Min       1Q   Median       3Q      Max  
-3.3725  -0.3725   0.6275   0.6275   1.2222  

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  3.37255    0.09601  35.126   <2e-16 ***
Rural       -0.59477    0.24790  -2.399    0.018 *  
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.9402902)

    Null deviance: 116.37  on 119  degrees of freedom
Residual deviance: 110.95  on 118  degrees of freedom
AIC: 337.14

Number of Fisher Scoring iterations: 2

> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Twentyone ~ Rural)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 29.153 24.152 35.189 < 2.2e-16 ***
Rural        0.552  0.339  0.897    0.0180 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -7.542     Nagelkerke R2: 0.05


> wit <- glm(formula = Seven~ Academic)
> summary(wit)

Call:
glm(formula = Seven ~ Academic)

Deviance Residuals: 
   Min      1Q  Median      3Q     Max  
-2.139  -0.750   0.250   0.250   1.250  

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  3.75000    0.09741  38.496   <2e-16 ***
Academic     0.38889    0.17785   2.187   0.0307 *  
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

(Dispersion parameter for gaussian family taken to be 0.797081)

    Null deviance: 97.867  on 119  degrees of freedom
Residual deviance: 94.056  on 118  degrees of freedom
AIC: 317.31

Number of Fisher Scoring iterations: 2

> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Seven ~ Academic)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 42.521 35.131 51.466 < 2.2e-16 ***
Academic     1.475  1.041  2.091    0.0307 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -11.116     Nagelkerke R2: 0.042


> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Thirteen ~ Academic)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 35.993 29.279 44.247 < 2.2e-16 ***
Academic     1.695  1.163  2.471    0.0070 ** 
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -10.317     Nagelkerke R2: 0.064



> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Fifteen ~ Academic)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 42.018 35.196 50.162 < 2.2e-16 ***
Academic     1.412  1.022  1.952    0.0386 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -10.942     Nagelkerke R2: 0.039


OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Eighteen ~ Academic)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 69.276 57.595 83.326 < 2.2e-16 ***
Academic     1.412  1.008  1.979    0.0470 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -14.533     Nagelkerke R2: 0.036


OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Twentyone ~ Academic)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 23.447 19.042 28.872 < 2.2e-16 ***
Academic     1.535  1.050  2.245    0.0290 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -7.536     Nagelkerke R2: 0.042



Waiting for profiling to be done...

Call:
glm(formula = Twentytwo ~ Academic)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 21.317 17.095 26.582 < 2.2e-16 ***
Academic     1.553  1.038  2.324    0.0342 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -7.036     Nagelkerke R2: 0.04


OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Twentythree ~ Academic)

Odds Ratios:
                or or.lci or.uci  Pr(>|z|)    
(Intercept) 20.326 16.157 25.571 < 2.2e-16 ***
Academic     1.629  1.071  2.477    0.0243 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -6.867     Nagelkerke R2: 0.044


> OddsRatio(wit)
Waiting for profiling to be done...

Call:
glm(formula = Twentyfour ~ Academic)

Odds Ratios:
               or or.lci or.uci  Pr(>|z|)    
(Intercept) 4.930  4.056  5.992 < 2.2e-16 ***
Academic    1.499  1.050  2.140    0.0279 *  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1 

Brier Score: -1.265     Nagelkerke R2: 0.043
