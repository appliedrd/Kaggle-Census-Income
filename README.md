# Kaggle-Census-Income
Classification done using Tensorflow and sklearn

The data here is for the **"Census Income"** dataset, which contains data on adults from the 1994 census. This data is labeled with whether the person's yearly income is above or below $50K (and you are trying to model and predict this).

The data contains the following columns, along with a brief description of the data type (either "continuous" for numerical values, or a list of categorical values):

 - **age:** continuous.
 - **workclass:** Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
fnlwgt: continuous.
 - **education:** Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
education-num: continuous.
 - **marital-status:** Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
 - **occupation:** Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct,   Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
 - **relationship:** Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
 - **race:** White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
 - **sex:** Female, Male.
 - **capital-gain:** continuous.
 - **capital-loss:** continuous.
 - **hours-per-week:** continuous.
 - **native-country:** United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.


**Output**
adult.data contains one additional column for the label, which is >50K if the person's yearly income is greater than $50K, and otherwise <=50K.
