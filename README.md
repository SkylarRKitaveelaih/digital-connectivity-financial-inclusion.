Digital Connectivity and Financial Inclusion Across Developing Economies

Overview

This project examines the relationship between digital connectivity and financial inclusion across developing economies using individual-level data from the World Bank Global Findex 2025.

The analysis focuses on two dimensions of digital connectivity:

* Mobile-phone ownership
* Internet use

It then compares how these factors are associated with two forms of financial participation:

* Mobile-money accounts
* Traditional financial-institution accounts

The goal is to examine whether digital connectivity is associated with participation in the financial system and whether that relationship differs between mobile and traditional financial services.

Research Question

How is digital connectivity associated with financial inclusion across developing economies, and does that relationship differ between mobile-money accounts and traditional financial-institution accounts?

Data

The project uses individual-level microdata from the World Bank Global Findex 2025.

The primary analysis includes approximately 69,500 adults across 70 developing economies spanning:

* Sub-Saharan Africa
* Latin America & the Caribbean
* East Asia & the Pacific
* Middle East & North Africa
* Europe & Central Asia

The original World Bank microdata are not redistributed in this repository.

Methodology

The analysis uses logistic regression to estimate the association between digital connectivity and financial account ownership.

The primary specifications incorporate:

* Mobile-phone ownership
* Internet use
* Age
* Gender
* Education
* Income quintile
* Employment status
* Urban/rural residence
* Country fixed effects
* World Bank respondent survey weights

Additional analyses include:

* Phone ownership × internet-use interaction models
* Income interaction analysis
* Gender and urban/rural interaction tests
* Regional robustness analysis
* Unweighted models with country-clustered standard errors
* Adjusted predicted probabilities across connectivity profiles

Because the Global Findex data are cross-sectional and observational, the results are interpreted as associations rather than causal effects.

Key Findings

1. Digital connectivity is strongly associated with mobile-money participation.

In the weighted country-fixed-effects model, both mobile-phone ownership and internet use were positively associated with mobile-money account ownership after controlling for demographic and socioeconomic characteristics.

After additionally accounting for phone ownership, internet use remained strongly associated with mobile-money participation.

2. The relationship extends beyond simply owning a mobile phone.

Controlling for mobile-phone ownership reduced the estimated association between internet use and mobile-money ownership, but did not eliminate it.

In the primary weighted specification:

* Internet use: Odds Ratio ≈ 2.69
* Mobile-phone ownership: Odds Ratio ≈ 5.34

This suggests that device ownership and broader digital connectivity capture distinct dimensions of the relationship between technology access and mobile financial participation.

3. Digital connectivity is associated with both mobile and traditional financial participation, but the association is stronger for mobile money.

Outcome	Internet Use OR	Phone Ownership OR
Mobile-money account	2.69	5.34
Any financial account	2.32	3.17
Financial-institution account	2.08	1.92

Phone ownership, in particular, shows a substantially stronger association with mobile-money participation than with traditional financial-institution account ownership.

4. Adjusted financial participation rises across connectivity profiles.

Interaction-adjusted predicted probabilities were:

Connectivity Profile	Mobile Money	Financial Institution
No phone + no internet	8.51%	27.76%
Internet only	21.28%	39.74%
Phone only	27.06%	38.00%
Phone + internet	41.47%	50.64%

Moving from neither form of connectivity to both phone ownership and internet use corresponds with an increase in adjusted mobile-money participation from approximately 8.5% to 41.5%.

5. The relationship is not driven solely by Sub-Saharan Africa.

Separate regional models found a positive association between internet use and mobile-money participation across all five developing-economy regions examined.

Region	Internet Use OR
Sub-Saharan Africa	2.64
Middle East & North Africa	3.28
East Asia & Pacific	3.60
Latin America & Caribbean	3.68
Europe & Central Asia	10.49

Regional estimates should be interpreted cautiously because baseline mobile-money adoption and financial systems differ substantially across regions. The regional analysis is used primarily as a robustness check rather than as evidence of causal differences between regions.

Interpretation

The results indicate a consistent relationship between digital connectivity and financial participation across developing economies.

Mobile-phone ownership is particularly strongly associated with mobile-money participation, while internet use remains independently associated with participation even after phone ownership and socioeconomic characteristics are taken into account.

The findings suggest that access to a device and broader engagement with digital infrastructure may represent distinct dimensions of financial inclusion.

Limitations

Several limitations are important when interpreting the results.

First, this analysis is observational. It cannot establish that phone ownership or internet use causes financial inclusion. Unobserved characteristics may influence both technology access and financial participation.

Second, the analysis uses available Global Findex respondent weights but does not implement a complete complex-survey estimator incorporating all potential primary sampling unit and stratification information.

Third, financial systems, mobile-money infrastructure, regulation, and technology adoption differ substantially across countries. Country fixed effects account for time-invariant differences between economies within the cross-sectional dataset, but they cannot account for every institutional difference or individual-level source of confounding.

Tools

The analysis was conducted in Google Colab using AI-assisted Python, including:

* pandas
* NumPy
* statsmodels
* Matplotlib

AI tools assisted with code development and debugging. Research-question development, model selection, interpretation, robustness testing, and conclusions were evaluated iteratively against the underlying data and statistical results.

Repository Contents

Global_Findex_Mobile_Money_Analysis.ipynb contains the data preparation, exploratory analysis, statistical models, robustness checks, and adjusted probability calculations used in this project.

Data Source

World Bank Global Findex Database 2025 — Connectivity and Financial Inclusion in the Digital Economy

The raw microdata are available through the World Bank Microdata Library and are not included in this repository.
