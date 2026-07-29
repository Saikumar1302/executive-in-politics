Starting Replication Process...

--- PART 1: TABLE 1 SUMMARY STATISTICS ---
Total Unique Politicians: 374
Total Business Politicians: 374
Percentage of Business Politicians who are Republican: 66.6%

Percentage of candidates who self-funded over $1 Million: 7.6%

--------------------------------------------------
PART 2: GENERATING ALL FIGURES...
--------------------------------------------------
Saved Figure 1 as 'Figure1.png'
Saved Figure 2 as 'Figure2.png'
Saved Figure 3 as 'Figure3.png'
Saved Figure 4 as 'Figure4.png'
Saved Figure 5 as 'Figure5.png'

--- PART 3: REGRESSIONS AND STATISTICAL TESTS ---

--- Table 3: Early Fundraising Advantage ---
businessPoliticianFlag    264.701168
REP_Flag                   25.524295
Incumbent_Flag            128.579284
dtype: float64

--- Table 7: Firm-Value Stock Returns (Event Study) ---
Window (-1 to +x days) | Average Return | t-statistic | p-value
CAR_Window_1           | 0.677%       | 5.30        | 0.000
CAR_Window_2           | 0.703%       | 3.94        | 0.000
CAR_Window_3           | 0.894%       | 4.22        | 0.000
CAR_Window_4           | 0.932%       | 4.16        | 0.000

--- Table 8: Committee Assignments ---
same_industry_exp    0.062589
seniority           -0.000943
powerful_cmt         0.027198
dtype: float64

--- Tables 11 & 12: Legislative Voting Impact ---

Target Variable: CFA
                         Effect Size (Coef)        P-Value
SeniorExecutiveVerified           -5.638895   4.776731e-04
repFlag                          -44.823776  1.386880e-243

Target Variable: COPE
                         Effect Size (Coef)   P-Value
SeniorExecutiveVerified           -6.219501  0.001156
repFlag                          -60.643641  0.000000

Target Variable: CCUS
                         Effect Size (Coef)        P-Value
SeniorExecutiveVerified            4.432631   2.186391e-03
repFlag                           42.963445  5.035981e-272

Target Variable: dwnom1
                         Effect Size (Coef)   P-Value
SeniorExecutiveVerified            6.036377  0.000976
repFlag                           62.140434  0.000000

Replication Complete! Check your folder for the saved .png charts.
