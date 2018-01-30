# Prediction_of_LGD
Prediction of LGD
PD (Probability of default) is crucial for assessing the risk incurred by lenders, but does not give the complete picture. Lenders also need to assess the magnitude of losses that arise in the event of default. In literature loss magnitude usually expressed as a percentage loss rate, LGD.

Variables used for predicting LGD
instrument related
firm-specific
macroeconomic
industry specific

Instrument related variables: in the event of default not all barrowers are equal. Some are more senior than others. some debt instruments are secured giving the debt holders the right to claim specific assets connected with the instrument. Average historical LGDs for different debt types are shown on the side. 
In a regression model we can capture such average differences in two alternative ways.
Create one variable that contains the historical average LGD of the respective debt type or introduce a dummy variable for debt types. 
 
Firm specific variables: the overall losses incurred by creditors will equal the value of liabilities minus the value of the firm's assets after bankruptcy costs. we can therefore increase the predictive accuracy if we find variables that contain information about the post-default asset value or bankruptcy costs. 

tangibility: (tangible assets) property, plant, equipment / total assets: higher this ratio lower the LGD
market to book ratio: Tobin's Q: (market value of equity + book value of liabilities) / total assets: the higher the ratio the higher the firm's market value, so lower the LGD.
Leverage: total debt / total assets: usually expected to be positively correlated with the LGD.

macroeconomic variables: in many cases the figures for the country in which the borrower is domiciled or generated largest part of income is used. 
Capacity utilization: low capacity utilization means demand for firm's assets is low, because competitors do not need additionel production capacity. this leads to a high LGD
GDP growth: a negative economic environment leads high LGD
Corporate bond spreads: the asset value will fall with the increasing discount rates. the higher the spread the higher the expected LGD.
default rates: high default rates indicate negative economic environment and lead high LGD.

industry variables: capacity utilization same as above
market to book ratio: checking industry average to assess the firm.
