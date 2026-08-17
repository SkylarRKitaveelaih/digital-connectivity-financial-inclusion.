Digital Connectivity and Financial Inclusion Across Developing Economies

Overview

How closely is access to digital technology associated with access to financial services?

This project examines the relationship between digital connectivity and financial inclusion across developing economies using individual-level data from the World Bank Global Findex 2025.

I focus on two dimensions of digital connectivity:

* Mobile-phone ownership
* Internet use

I compare their relationships with two forms of financial participation:

* Mobile-money accounts
* Traditional financial-institution accounts

The analysis uses approximately 69,500 respondents across 70 developing economies, allowing the relationship between connectivity and financial participation to be examined across countries, regions, and socioeconomic groups.

⸻

Research Question

How is digital connectivity associated with financial inclusion across developing economies, and does that relationship differ between mobile-money accounts and traditional financial-institution accounts?

⸻

Data

The analysis uses individual-level microdata from the World Bank Global Findex 2025.

The initial developing-economy sample contained 90,923 respondents. Among respondents for whom mobile-money account status was observed, 70,893 respondents across 71 economies were available.

After removing observations missing variables required for the primary regression specification, the final analysis sample contained approximately 69,500 respondents across 70 economies.

The sample spans five World Bank developing-economy regions:

* Sub-Saharan Africa
* Latin America & Caribbean
* East Asia & Pacific
* Middle East & North Africa
* Europe & Central Asia

The raw World Bank microdata are not redistributed in this repository.

⸻

Variables

Financial inclusion outcomes

Mobile-money account (account_mob)
Indicates whether a respondent has a mobile-money account.

Financial-institution account (account_fin)
Indicates whether a respondent has an account at a traditional financial institution.

Main connectivity variables

Internet use (internet_use)
Indicates whether the respondent uses the internet.

Mobile-phone ownership (con1)
The Global Findex connectivity variable was recoded into a binary indicator identifying respondents who personally own a mobile phone.

Controls

The models additionally account for:

* Age
* Gender
* Education
* Income quintile
* Employment status
* Urban/rural residence
* Economy

⸻

Methodology

Because the primary outcomes are binary, I use logistic regression to estimate the relationship between digital connectivity and financial participation.

The primary models incorporate:

* World Bank respondent survey weights
* Economy fixed effects
* Demographic and socioeconomic controls

The main specification can be represented conceptually as:

Financial participation = f(Internet use, Phone ownership, Demographics, Socioeconomic characteristics, Economy)

I also estimate interaction models to determine whether the relationship associated with having both forms of connectivity differs from what would be expected from their individual associations.

Additional analyses include:

* Internet × phone-ownership interaction models
* Income × internet interaction models
* Gender × internet interaction tests
* Urbanicity × internet interaction tests
* Regional robustness models
* Unweighted models with economy-clustered standard errors
* Adjusted predicted probabilities

Because these data are cross-sectional and observational, all results are interpreted as associations rather than causal effects.

⸻

Results

1. Digital connectivity is strongly associated with mobile-money participation

In the primary weighted model with economy fixed effects and socioeconomic controls, both internet use and mobile-phone ownership were positively associated with mobile-money account ownership.

Connectivity Variable	Odds Ratio
Internet use	2.69
Mobile-phone ownership	5.34

Holding the other included characteristics constant, phone ownership showed the larger association with mobile-money participation.

Importantly, internet use remained strongly associated with mobile-money participation even after accounting for whether the respondent owned a phone.

⸻

2. Financial participation differs substantially across connectivity profiles

The interaction model was used to estimate adjusted probabilities for four connectivity profiles.

Connectivity Profile	Mobile Money	Financial Institution
No phone + no internet	8.51%	27.76%
Internet only	21.28%	39.74%
Phone only	27.06%	38.00%
Phone + internet	41.47%	50.64%

Adjusted mobile-money participation increases from approximately 8.5% among respondents with neither form of connectivity to 41.5% among respondents with both.

For mobile money specifically, respondents in the phone-only profile also have a higher adjusted probability than respondents in the internet-only profile.

Main Figure

Adjusted predicted probabilities from weighted logistic regression models with economy fixed effects and demographic and socioeconomic controls.

⸻

3. Connectivity has a stronger relationship with mobile money than with traditional financial accounts

The association between connectivity and financial participation differs depending on the type of financial account examined.

Outcome	Internet Use OR	Phone Ownership OR
Mobile-money account	2.69	5.34
Any financial account	2.32	3.17
Financial-institution account	2.08	1.92

The difference is particularly pronounced for phone ownership.

Phone ownership is associated with approximately 5.34 times the odds of mobile-money participation, compared with approximately 1.92 times the odds of traditional financial-institution account ownership, conditional on the variables included in the models.

This suggests that digital connectivity is relevant to financial participation generally, but is especially closely associated with participation through mobile-money systems.

⸻

4. Phone ownership and internet use overlap in their relationship with mobile money

The phone × internet interaction was statistically significant for mobile-money participation:

* Interaction coefficient: −0.419
* Interaction odds ratio: 0.658
* p-value: < 0.001

The negative interaction does not mean that having both forms of connectivity is associated with lower mobile-money participation. Respondents with both still have the highest adjusted probability of mobile-money ownership.

Instead, the result indicates that the combined association is smaller than a simple multiplicative-odds model would predict.

For traditional financial-institution accounts, the corresponding interaction was not statistically significant (p = 0.470).

⸻

5. The internet association appears across all five regions examined

To test whether the pooled result was primarily driven by the large Sub-Saharan African portion of the sample, I estimated the mobile-money model separately across five developing-economy regions.

Region	Respondents	Internet Use OR
Sub-Saharan Africa	32,882	2.64
Middle East & North Africa	8,020	3.28
East Asia & Pacific	8,050	3.60
Latin America & Caribbean	14,582	3.68
Europe & Central Asia	5,983	10.49

Internet use was positively associated with mobile-money participation in every region examined.

Regional Robustness Figure

Regional odds ratios are used as a robustness check. Differences in the magnitude of the regional estimates should not be interpreted as causal differences between regions.

⸻

6. The relationship is not limited to higher-income respondents

I also examined adjusted mobile-money probabilities across income quintiles.

Income Quintile	No Internet	Internet	Difference
1	15.95%	34.07%	+18.12 pp
2	19.56%	38.25%	+18.70 pp
3	22.31%	39.48%	+17.17 pp
4	24.54%	42.76%	+18.22 pp
5	24.69%	45.53%	+20.84 pp

Internet users have higher adjusted predicted mobile-money participation in every income quintile.

However, the interaction results do not support a simple conclusion that the internet relationship systematically becomes stronger or weaker as income rises.

⸻

Interpretation

The analysis identifies a consistent relationship between digital connectivity and financial participation across developing economies.

Three findings stand out.

First, mobile-phone ownership is strongly associated with mobile-money participation.

Second, internet use remains independently associated with mobile-money participation even after accounting for phone ownership, socioeconomic characteristics, and differences between economies.

Third, connectivity is associated with traditional financial participation as well, but the relationship—particularly for phone ownership—is substantially stronger for mobile money.

Taken together, the results suggest that device access and broader digital connectivity represent related but distinct dimensions of financial inclusion.

The findings do not establish that expanding phone or internet access would itself cause increases in financial inclusion. Instead, they identify patterns that may motivate further research into the mechanisms linking digital infrastructure, financial technology, and access to financial services.

⸻

Robustness Checks

The analysis includes several checks of the primary result:

Economy fixed effects
Models account for persistent differences across the 70 economies represented in the final regression sample.

Survey weights
Primary models incorporate Global Findex respondent weights.

Economy-clustered standard errors
An unweighted specification with standard errors clustered by economy produced similar estimates:

* Internet OR: 2.81
* Phone ownership OR: 5.05

Regional models
Positive internet associations were observed separately across all five developing-economy regions examined.

Alternative financial outcomes
Connectivity remained positively associated with overall account ownership and traditional financial-institution account ownership, although the magnitude differed from mobile money.

⸻

Limitations

This project has several important limitations.

Association is not causation

The Global Findex data are observational and cross-sectional. The analysis therefore cannot establish that internet access or phone ownership causes financial inclusion.

For example, income, infrastructure, institutional quality, financial development, or other characteristics could influence both connectivity and financial participation.

Survey design

The analysis incorporates available respondent weights but does not implement a complete complex-survey estimator using all potential sampling strata and primary sampling units.

Cross-country heterogeneity

Financial systems, mobile-money infrastructure, regulation, telecommunications markets, and economic conditions vary substantially across economies.

Economy fixed effects account for systematic differences between countries within the cross-sectional sample, but they cannot eliminate every potential source of confounding.

Mobile-money availability

Mobile-money services differ considerably across countries. The existence and maturity of mobile-money ecosystems may influence both adoption levels and the observed relationship with connectivity.

⸻

Repository Structure

digital-connectivity-financial-inclusion/
│
├── README.md
├── Global_Findex_Mobile_Money_Analysis.ipynb
│
└── outputs/
    ├── connectivity_financial_inclusion_figure.png
    ├── regional_internet_mobile_money_figure.png
    ├── main_connectivity_regression.csv
    ├── connectivity_account_comparison.csv
    ├── regional_robustness_results.csv
    ├── income_adjusted_probabilities.csv
    └── phone_internet_interactions.csv

⸻

Reproducing the Analysis

The analysis notebook contains the data preparation, variable construction, regression models, interaction tests, adjusted probability calculations, robustness checks, and visualization code.

To reproduce the analysis:

1. Obtain the World Bank Global Findex 2025 microdata from the World Bank Microdata Library.
2. Open Global_Findex_Mobile_Money_Analysis.ipynb in Google Colab or another Jupyter environment.
3. Load the Global Findex CSV file.
4. Run the notebook cells in sequence.

The raw microdata are intentionally not included in this repository.

⸻

Tools

Analysis was conducted in Google Colab using AI-assisted Python.

Primary libraries:

* pandas
* NumPy
* statsmodels
* Matplotlib

AI tools assisted with code development and debugging. Model specifications, statistical outputs, robustness checks, and interpretations were evaluated iteratively against the underlying data.

⸻

Data Source

World Bank — Global Findex Database 2025

Connectivity and Financial Inclusion in the Digital Economy

Raw microdata are available through the World Bank Microdata Library and are not redistributed in this repository.
