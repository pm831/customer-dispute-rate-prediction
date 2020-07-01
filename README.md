# Consumer Complaints Dispute Rate Prediction & Data Visualization
### Pujan Malavia
![cfpb](https://user-images.githubusercontent.com/19572673/62312334-eba51900-b45b-11e9-87f0-ba0e94c8e402.png)


![ComplaintsAnalysis](https://user-images.githubusercontent.com/19572673/57265265-cebb9e00-7044-11e9-95f3-ef2625564c23.PNG)

### Abstract:
Each week the American Consumer Financial Protection Bureau (CFPB) sends thousands of consumers’ complaints about financial products and services to companies for response. Those complaints are published here CFPB after the company responds or after 15 days. By adding their voice, consumers help improve the financial marketplace get their voices heard.

https://www.kaggle.com/cfpb/us-consumer-finance-complaints

### Industry: 
Government Administration/Financial Services

### Company Information:
The Consumer Financial Protection Bureau (CFPB) is an agency of the United States government responsible for consumer protection in the financial sector. CFPB's jurisdiction includes banks, credit unions, securities firms, payday lenders, mortgage-servicing operations, foreclosure relief services, debt collectors and other financial companies operating in the United States. 

https://en.wikipedia.org/wiki/Consumer_Financial_Protection_Bureau

https://www.consumerfinance.gov/

### Use Case:
Figuring out specific Companies, Products, and Sub-Products with the most number of Complaints

### Initial Dataset(s):
Consumer Complaints Classification

### Software:
Python, PowerBI

### Techniques:

Random Forest

### Basic Steps:

Downloaded the dataset. 

Categorical slicers include State, Zip Code, Company, Complaint ID, Submitted Via, Product, Sub-Product, Issue, Sub-Issue, Company Public Response, Company Response to Customer, Timely Response? Consumer Disputed, Tags, Cons. Consent Provided?, Numerical slicer includes the 'date range' (where you can slide accordingly)

State: A typical U.S. State displayed

Zip Code: Only first 3 digits displayed due to confidentiality purposes

Company: Unique name of company

Complaint ID: Unique Complaint ID assigned to complaint transaction

Submitted Via

Product

Sub-Product

Issue: Various issues listed pertaining to complaint

Sub-Issue: Various sub-issues listed pertaining to the issue at hand

Complany Public Response

Company Response to Customer

Timely Response? 

Consumer Disputed

Tags

Date Range:

![Customer_Complaints_Slicers](https://user-images.githubusercontent.com/19572673/60402039-bdc86e00-9b57-11e9-8f48-39832bcb0c72.PNG)

Number of Complaints by State

![Customer_Complaints_By_State](https://user-images.githubusercontent.com/19572673/60402036-bdc86e00-9b57-11e9-92bf-a0087afb2532.PNG)

Number of Complaints by Company

![Customer_Complaints_By_Company](https://user-images.githubusercontent.com/19572673/60402033-bdc86e00-9b57-11e9-943d-ba0ad66150f2.PNG)

Number of Complaints by Product

![Customer_Complaints_By_Product](https://user-images.githubusercontent.com/19572673/60402034-bdc86e00-9b57-11e9-8839-0f8eabbc7e87.PNG)

Number of Complaints by Sub-Product

![Customer_Complaints_By_Sub_Product](https://user-images.githubusercontent.com/19572673/60402037-bdc86e00-9b57-11e9-8a9c-f4090c8e7e1d.PNG)

Number of Complaints by Product (Pie Chart)

![Customer_Complaints_By_Product_Pie](https://user-images.githubusercontent.com/19572673/60402035-bdc86e00-9b57-11e9-9930-a5b10e49d35f.PNG)

Number of Complaints Daily

![Customer_Complaints_Daily](https://user-images.githubusercontent.com/19572673/60402038-bdc86e00-9b57-11e9-88d0-5e19bc791d77.PNG)

Complaints Tabular Report

![Customer_Complaints_Tabular_Report](https://user-images.githubusercontent.com/19572673/60402040-bdc86e00-9b57-11e9-8fc2-63e932c2ec61.PNG)

### Data Visualization

Python (Jupyter Notebook) Visualizations

Complaint Dispute Rate vs. Company Complaint Counts

![output_39_0](https://user-images.githubusercontent.com/19572673/85910989-0f99e780-b7f0-11ea-893f-b9aeadc30280.png)

Customer Disputed Response by Product

![output_41_1](https://user-images.githubusercontent.com/19572673/85910990-10327e00-b7f0-11ea-96d2-6d3b74579cbd.png)

Customer Disputed Response by Company Response to Consumer

![output_43_1](https://user-images.githubusercontent.com/19572673/85910991-10327e00-b7f0-11ea-91e8-88a04671847e.png)

Customer Disputed Response by Product

![output_45_1](https://user-images.githubusercontent.com/19572673/85910992-10327e00-b7f0-11ea-883e-f2084773cc0a.png)

Confusion Matrix of Response Variable (from Random Forest Model)

![output_84_1](https://user-images.githubusercontent.com/19572673/85910993-10cb1480-b7f0-11ea-8c00-2008a75d9929.png)

Variable Importance Plot #1 (Random Forest)

![output_86_0](https://user-images.githubusercontent.com/19572673/85910994-10cb1480-b7f0-11ea-8ca2-e0b20757f984.png)

Variable Importance Plot #2 (Random Forest)

![output_104_0](https://user-images.githubusercontent.com/19572673/85910995-10cb1480-b7f0-11ea-84ee-735519623998.png)

SGD Classifier Curve Plot

![output_116_0](https://user-images.githubusercontent.com/19572673/85910996-10cb1480-b7f0-11ea-9251-545fc53b0225.png)

### Communication of Results to Business Partner:
To a business partner, I would explain that the Random Forest (all else equal) would work better for complex data (high variance, low bias) that’s a bit more unknown in terms of predictors’ effect on the response variable since it looks at all predictor variables equally in terms of its importance.

### Future Work:
Continue to do hyperparameter tuning of the model and creating new features/removing old features to help increase the prediction accuracy of the model

Try other types of models to see if the accuracy rate improves

More data visualization/patterns within the dataset (external sources) that can lead to more insights and decision-making from a business perspective
