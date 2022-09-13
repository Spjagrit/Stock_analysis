# Stock_analysis

Firstly I have validated the data based on sub-sectors division, created a pie chart for visually representing it and thus created a pivot table for each specification (i.e Large cap(>20000cr), Mid-cap((5000-20000)cr) and small-cap (<5000cr)).I then used a column chart to visually represent the aforesaid specification of the dataset.
The Random selection of the company has been done on the basis of Higher Market Capital and higher 5Y CAGR because validating on the basis of CAGR helps one's company to measure its investments' average annual growth over a given period. It precisely measures investment growth (or decline) over time. I then calculated the intrinsic value for all 10 companies based on 3 cases of growth (g): Assume 3 Cases for g (Growth): Good (15% Growth); Bad (-5% Growth); Best (25%Growth) and finally plotted a line graph based on the above value (i.e. V1(Good Intrinsic Value), V2(Bad Intrinsic Value), V3(Best Intrinsic Value) and market capital. ).


Note:- The intrinsic value is calculated by using the formula-


                          V = (EPS * (8.5 + 2g) * 6) / Y
                          
                          
Where,
V: [Intrinsic Value]
EPS: [The Company’s last 12-month earnings per share]
8.5: [The constant represents the appropriate P-E ratio for a no-growth company as   proposed by Graham.]
g : [The company's long-term (five years) earnings growth estimate]
6 : [The average Return of FDs (6%)]
Y : [The current yield on AAA corporate bonds.]
