Digital Connectivity and Financial Inclusion Across Emerging and Developing Economies

Overview

This project examines whether mobile-phone ownership and internet use are associated with financial participation, with a particular focus on mobile money.

Using individual-level data from the World Bank Global Findex 2025, I compare the relationship between digital connectivity and two forms of financial participation:

* Mobile-money account ownership
* Financial-institution account ownership

The primary phone-and-internet analysis includes 69,517 respondents across 70 economies represented in five World Bank regional categories excluding high-income economies.

Research question: How is digital connectivity associated with financial inclusion across the economies examined, and does that relationship differ between mobile-money and financial-institution accounts?

⸻

Data and Sample

The project uses individual-level microdata from the World Bank Global Findex 2025.

I restricted the dataset to World Bank regional categories explicitly labeled as excluding high-income economies and then to respondents for whom mobile-money account status was observed.

This produced:

* 90,923 respondents in the initial regional subset
* 70,893 respondents with observed mobile-money account status across 71 economies
* 69,549 complete observations in the initial internet-use regression
* 69,517 complete observations across 70 economies in the primary phone-and-internet specification

The final phone-and-internet sample covers:

* Sub-Saharan Africa
* Latin America & Caribbean
* East Asia & Pacific
* Middle East & North Africa
* Europe & Central Asia

These five regions reflect the filtering rule used in this project and should not be interpreted as a comprehensive sample of every low- and middle-income economy or region.

The raw Global Findex microdata are not redistributed in this repository.

⸻

Variables

Outcomes

Mobile-money account (account_mob)
Binary indicator of mobile-money account ownership.

Financial-institution account (account_fin)
Binary indicator of account ownership at a financial institution.

I also examine overall account ownership (account) as an alternative outcome.

Digital connectivity

Internet use (internet_use)
Binary indicator of internet use.

Mobile-phone ownership (con1)
For the primary connectivity analysis, con1 == 1 was coded as phone ownership and con1 == 2 as non-ownership. The small number of observations coded 3 or 4 were excluded from this binary measure.

Controls

Models additionally include:

* Age
* Gender
* Education
* Income quintile
* Employment status
* Urban/rural residence
* Economy fixed effects

⸻

Methodology

Because the outcomes are binary, the primary analysis uses binomial generalized linear models with a logit link.

The main models incorporate Global Findex respondent weights and economy fixed effects while adjusting for demographic and socioeconomic characteristics.

The primary specification is conceptually:

Mobile-money ownership ~ Internet use + Phone ownership + Demographic controls + Socioeconomic controls + Economy fixed effects

Additional analyses examine:

* Phone ownership × internet-use interactions
* Internet-use heterogeneity across income quintiles
* Gender × internet-use interactions
* Urban/rural × internet-use interactions
* Separate regional specifications
* An unweighted specification with economy-clustered standard errors
* Alternative financial-account outcomes
* Adjusted predicted probabilities

Because the data are cross-sectional and observational, the estimates describe conditional associations. They do not identify causal effects.

⸻

Main Results

1. Phone ownership and internet use are both associated with mobile-money ownership

In the weighted phone-and-internet specification, controlling for demographic and socioeconomic characteristics and economy fixed effects:

Connectivity measure	Odds ratio
Internet use	2.69
Phone ownership	5.34

Internet users had approximately 2.69 times the estimated odds of mobile-money account ownership relative to non-users, conditional on the included covariates.

Phone owners had approximately 5.34 times the estimated odds relative to non-owners under the same specification.

The persistence of the internet coefficient after including phone ownership suggests that the internet-use association is not explained solely by whether respondents own a mobile phone.

⸻

2. Adjusted probabilities differ substantially across connectivity profiles

A model allowing phone ownership and internet use to interact produced the following adjusted predicted probabilities:

Connectivity profile	Mobile money	Financial institution
No phone + no internet	8.51%	27.76%
Internet only	21.28%	39.74%
Phone only	27.06%	38.00%
Phone + internet	41.47%	50.64%

For mobile money, the adjusted probability rises from 8.5% for the neither-connectivity profile to 41.5% for the phone-and-internet profile.

Adjusted predicted probabilities from weighted logit models with economy fixed effects and demographic and socioeconomic controls.

⸻

3. Phone ownership is much more strongly associated with mobile money than with financial-institution accounts

The same connectivity measures were estimated for alternative financial-account outcomes:

Outcome	Internet-use OR	Phone-ownership OR
Mobile-money account	2.69	5.34
Any financial account	2.32	3.17
Financial-institution account	2.08	1.92

The contrast is largest for phone ownership: its estimated odds ratio is 5.34 for mobile money compared with 1.92 for financial-institution accounts.

This pattern is consistent with mobile connectivity being more closely associated with mobile-money participation than with conventional financial-institution account ownership.

⸻

4. Phone and internet connectivity are not simply additive on the log-odds scale

For mobile-money ownership, the phone × internet interaction was negative and statistically significant:

Measure	Estimate
Interaction coefficient	−0.419
Interaction OR	0.658
p-value	< 0.001

This does not imply that having both is associated with lower mobile-money participation. The phone + internet profile has the highest adjusted probability.

Rather, the estimated joint association is smaller on the multiplicative-odds scale than would be implied by multiplying the two main-effect odds ratios without an interaction.

For financial-institution accounts, the corresponding interaction was not statistically significant (p = 0.470).

⸻

5. The internet-use association is positive in each region examined

I estimated the primary mobile-money specification separately within each of the five regional groups:

Region	N	Internet-use OR
Sub-Saharan Africa	32,882	2.64
Middle East & North Africa	8,020	3.28
East Asia & Pacific	8,050	3.60
Latin America & Caribbean	14,582	3.68
Europe & Central Asia	5,983	10.49

The estimated internet-use association was positive in all five specifications.

These estimates are best interpreted as a robustness check. Their magnitudes should not be read as causal comparisons between regions because financial systems, mobile-money markets, connectivity, and sample composition differ substantially across them.

⸻

Income Heterogeneity

Adjusted predicted probabilities were also estimated across income quintiles:

Income quintile	No internet	Internet	Difference
1	15.95%	34.07%	+18.12 pp
2	19.56%	38.25%	+18.70 pp
3	22.31%	39.48%	+17.17 pp
4	24.54%	42.76%	+18.22 pp
5	24.69%	45.53%	+20.84 pp

Adjusted mobile-money probabilities are higher for internet users in each income quintile.

However, the interaction estimates are not monotonic across income quintiles, so these results do not support a simple claim that the internet association consistently strengthens or weakens with income.

⸻

Robustness Checks

Several analyses were used to assess whether the primary result was sensitive to modeling choices.

Unweighted model with economy-clustered standard errors

The unweighted specification produced similar point estimates:

* Internet-use OR: 2.81
* Phone-ownership OR: 5.05

Regional specifications

The estimated internet-use association remained positive in each of the five regional specifications.

Alternative outcomes

Both connectivity measures were also positively associated with overall account ownership and financial-institution account ownership, although the estimated magnitudes differed from those for mobile money.

Gender and urban/rural interactions

The internet × gender interaction was not statistically significant (p = 0.194), nor was the internet × urbanicity interaction (p = 0.160) in the corresponding weighted specifications.

⸻

Interpretation

The results show a consistent conditional association between digital connectivity and financial participation in the economies examined.

Three patterns are particularly notable:

1. Phone ownership is strongly associated with mobile-money ownership.
2. Internet use remains associated with mobile-money ownership even after accounting for phone ownership and observed socioeconomic characteristics.
3. Phone ownership has a substantially larger estimated association with mobile money than with financial-institution account ownership.

These findings are consistent with the idea that device ownership and broader digital connectivity capture related but distinct dimensions of participation in digital financial systems.

They do not establish that providing someone with a phone or internet access would cause that person to adopt mobile money.

⸻

Limitations

No causal identification

The analysis is observational and cross-sectional. Unobserved factors—including infrastructure, institutional conditions, financial development, technology adoption, or individual characteristics—may influence both connectivity and financial participation.

Survey design

The primary models use the available respondent weights, but the analysis does not implement a complete complex-survey estimator incorporating all sampling-design features.

Sample definition

The regional sample was constructed using World Bank regionwb categories explicitly containing the label "excluding high income". Consequently, the analysis should not be interpreted as representing every developing economy or every developing-world region.

Cross-economy heterogeneity

Economy fixed effects absorb differences in baseline log-odds across economies represented in the sample, but they do not remove unobserved individual-level confounding or establish causal identification.

Differences in mobile-money ecosystems

The availability, maturity, regulation, and use of mobile-money services vary substantially across economies. These differences may affect the relationships observed in the data.

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

The outputs/ directory contains the principal regression results, adjusted probabilities, robustness results, and figures used in this README.

⸻

Reproducing the Analysis

1. Obtain the World Bank Global Findex 2025 microdata from the World Bank.
2. Open Global_Findex_Mobile_Money_Analysis.ipynb in Google Colab or another Jupyter environment.
3. Update the input file path to point to the downloaded Global Findex CSV.
4. Run the analysis cells in sequence.

The raw microdata are intentionally not included in this repository.

⸻

Tools and Disclosure

The analysis was conducted in Google Colab using AI-assisted Python with:

* pandas
* NumPy
* statsmodels
* Matplotlib

AI assistance was used during code development and debugging. Statistical outputs were checked against the underlying model results, and the project distinguishes descriptive and associational evidence from causal claims.

⸻

Data Source

World Bank Global Findex Database 2025

The raw microdata used for this analysis are available from the World Bank and are not redistributed in this repository.
