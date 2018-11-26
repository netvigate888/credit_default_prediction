The best way to view the Jupyter Notebooks in this repository is to use the website http://nbviewer.jupyter.org. This link [Notebook Viewer](http://nbviewer.jupyter.org/github/netvigate888/credit_default_prediction/tree/master/) will take you straight to the website and the Notebook Viewer for this repository.

# Default Risk Analysis in the Low-Income Segment

Major financial institutions do not typically service well the needs of lower income families. Lending to low-income or first-time borrowers is challenging when there is little or no credit history. This creates a segment of ‘under-banked’ individuals struggling to access formal, safe and fairly priced credit. For established banks, this represents a profit growth opportunity, while for new entrants offering financial services, an attractive underserved market. However, to be successful in this segment, a financial institution must find non-traditional and creative ways to identify and mitigate default risk.

The work that follows will explore a dataset from a lender operating in this under-banked segment. The dataset contains details of loan applicants at the time of application plus a target variable indicating whether the applicant ultimately defaulted (target = 1) or not (target = 0). I will look for relationships between the characteristics of a loan applicant and their risk of default. For example, are people employed in a certain industry more likely to default, does length of employment, family status or size and location of residence impact default risk? Lastly, through the use of machine learning algorithms, I will attempt to predict the likelihood of default for a new loan applicant.

Notebook order of execution:
1. Initial_Processing
1. Attributes_from_Bureau_Data
1. Initial_EDA
1. Create_Baseline_Model
1. Correlation_Analysis_and_Dim_Reduction
1. Train_Test_Set_Creation
1. Predictive_Models
1. Improve_Models
1. Choosing_Final_Model
1. Performance_on_Test_Set
