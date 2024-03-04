# 1. Title and Author

- **Project Title:** Vehicle Insurance Claim Fraud Detection
- **Prepared for:** UMBC Data Science Master Degree Capstone by Dr. Chaojie (Jay) Wang
- **Author:** Harikiran Pallepati
- **GitHub:** https://github.com/harikiranpallepati/
- **LinkedIn:** https://www.linkedin.com/in/harikiran-pallepati-a37b99167/
- **PowerPoint Presentation:** 
- **YouTube Video:** 

# 2. Background

Vehicle insurance fraud involves individuals or groups conspiring to make false or exaggerated claims related to property damage or personal injuries following an accident. This deceptive practice can take various forms, such as staged accidents, phantom passengers claiming injuries who were not present at the scene, and false personal injury claims where injuries are exaggerated.

Insurance fraud can have significant financial implications for insurance companies, leading to increased costs and potentially higher premiums for honest policyholders. Detecting and preventing insurance fraud is crucial for maintaining the integrity of the insurance industry, ensuring fair premiums, and reducing the overall economic impact of fraudulent activities.

 **Research Questions:**
1. What are the most effective methods for detecting potential fraudulent insurance claims?
2. What are the common indicators or patterns associated with fraudulent claims in the vehicle insurance domain?

# 3. Data

## Data Source:
- Source: kaggle
- Source Link : https://www.kaggle.com/datasets/shivamb/vehicle-claim-fraud-detection/data

## Data Size
- Size of the dataset is 3MB.
- It consists of 15420 rows and 33 columns.
- Each row in your dataset represents a specific insurance claim. Each claim is associated with a set of attributes or features, capturing various details about the claim, the vehicle involved, the policyholder, and the circumstances surrounding the claim.

## Data Dictionary
* Month: The month in which the accident occurred.
* WeekOfMonth: The week of the month in which the accident occurred.
* DayOfWeek: The day of the week on which the accident occurred.
* Make: The make (brand) of the vehicle involved in the accident.
* AccidentArea: Whether the accident occurred in an urban or rural area.
* DayOfWeekClaimed: The day of the week on which the claim was filed.
* MonthClaimed: The month in which the claim was filed.
* WeekOfMonthClaimed: The week of the month in which the claim was filed.
* Sex: The gender of the policyholder.
* MaritalStatus: The marital status of the policyholder.
* Age: The age of the policyholder.
* Fault: Indicates whether the policyholder was at fault in the accident.
* PolicyType: The type of insurance policy associated with the claim.
* VehicleCategory: Category or type of the vehicle.
* VehiclePrice: Price category of the vehicle.
* FraudFound_P: The target variable indicating whether the claim is fraudulent (1) or not (0).
* PolicyNumber: Unique identifier for the insurance policy.
* RepNumber: Identifier for the insurance representative.
* Deductible: Deductible amount associated with the claim.
* DriverRating: Rating of the driver associated with the policy.
* Days_Policy_Accident: Time period between policy issuance and the accident.
* Days_Policy_Claim: Time period between policy issuance and filing the claim.
* PastNumberOfClaims: Number of past claims made by the policyholder.
* AgeOfVehicle: Age category of the vehicle.
* AgeOfPolicyHolder: Age group of the policyholder.
* PoliceReportFiled: Whether a police report was filed for the accident.
* WitnessPresent: Whether there were witnesses present during the accident.
* AgentType: Type of insurance agent associated with the claim.
* NumberOfSuppliments: Number of supplementary insurance policies.
* AddressChange_Claim: Change in address associated with the claim.
* NumberOfCars: Number of cars covered by the policy.
* Year: The year of the policy.
* BasePolicy: The base type of insurance policy.


## Target variable
The target variable, named FraudFound_P, indicates whether a claim application is fraudulent (1) or not (0).

