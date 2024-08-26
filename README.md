# IMPACT OF GROUP BASED INTERVENTIONS ON SYSTOLIC BLOOD PRESSURE REDUCTION
Hypertension is a critical public health issue globally, contributing to a
significant burden of cardiovascular diseases. Managing and reducing systolic blood pressure (SBP) is vital in preventing
HTN long-term complications.The BIGPIC study aimed to determine whether group-based
interventions—namely, MF (Microfinance) + GMV (Group Medical
Visits)—result in a greater reduction in SBP compared to the Usual Care (UC)
approach. The study also explored the influence of social determinants,
sociodemographic factors, lifestyle choices, and the International Wealth
Index (IWI) on SBP reduction over 12 months.

## Data and Methodology


### Data Description:

The dataset includes 2,891 hypertensive participants divided into two groups:
MF + GMV and Usual Care.

Baseline data and 12-month follow-up data were collected to evaluate
changes in SBP (Primary Outcome –12 months change in SBP).

The dataset encompasses variables such as social determinants,
socio-demographic factors, lifestyle factors, IWI scores, and others.
### Preprocessing and Feature Engineering:

Data preprocessing involved addressing missing data, normalizing
continuous variables, and encoding categorical variables(scales).

Feature engineering focused on quantifying social determinants,
categorizing lifestyle factors, and standardizing socio-demographic
variables.

Notably, interaction terms between IWI and lifestyle factors were created
to analyze their combined impact on SBP reduction.


### Model Selection

#### Model Selection, Training, and Evaluation:

Several models were considered - linear regression, random forest, and gradient
boosting machines (GBM). GBM due to superior performance in capturing complex relationships between
variables. The model was trained using the training dataset, with hyper-parameters
tuned through cross-validation to optimize performance.

Model evaluation using the testing dataset, where Mean Squared Error (MSE)
and R-squared were used to assess the predictive accuracy.

The GBM model demonstrated a strong ability to predict SBP reduction, with
significant predictors including group assignment (MF + GMV vs. UC), lifestyle
score, social determinants, and IWI.


## Results and Impact

### Key Findings:

The analysis revealed that participants in the MF + GMV group had a
significantly greater reduction in SBP compared to those in the UC group,Adjusting for socio-demographic factors, lifestyle choices, and IWI showed
reduction. The most influential predictors of SBP reduction were group assignment,
lifestyle factors (particularly diet and physical activity), and social
determinants like employment status and social support.

### Real-World Application:

These findings suggest that a structured group-based intervention (MF + GMV) is
more effective in long-term SBP management compared to standard care.

This approach could be implemented in public health strategies, particularly in
resource-constrained settings, to enhance hypertension control and reduce
cardiovascular risks.

The integration of socio-demographic and lifestyle factors into hypertension
management plans could further optimize outcomes.

## Challenges and Learnings

### Obstacles Overcome:

Managing the high dimensionality of the dataset, with numerous
socio-demographic and lifestyle variables. This is addressed through careful feature
selection and advanced modeling techniques like GBM.
Missing data, which was mitigated through imputation techniques.

### Lessons Learned:

The importance of a comprehensive approach to CDM that includes both clinical and
socio-behavioral factors.

Value of advanced ML techniques in uncovering complex patterns in health data.

## Conclusion

BIGPIC study demonstrated that the MF + GMV approach is more effective than
UC in reducing SBP over 12 months. Key predictors of SBP
reduction, including lifestyle factors and socio-demographic variables, were found.
Explore the scalability of the MF + GMV approach in different population settings,
and the long-term sustainability of SBP reductions achieved through group
interventions.
Integrating more granular social determinant data to refine predictive models for
hypertension management.












