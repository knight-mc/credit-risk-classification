# credit-risk-classification

#Analysis Overview:
  The analysis that was conducted sought to create a model with which to run a risk assessment on new loan applications based on the applicant’s available parameters. If the model is successful then it can be used to expedite the decision-making process on whether a loan application should be approved and whether the loan would be an acceptable risk based on company assessment or a high-risk loan that the company should turn away. 

#Results:
  •	Accuracy Score: 
    o	model shows approximately a 95% accuracy
  •	Precision Score: 
    o	model has a 1.0 (100% success rate) when identifying a healthy loan;
    o	model has only a .86 (86% success rate) when identifying a high-risk loan
  •	Recall Score: 
    o	model has a 1.0 (100% success rate) when identifying a healthy loan;
    o	model has only a .90 (90% success rate) when identifying a high-risk loan

#Summary:
  Based on the model’s precision and recall scores relating to high-risk loans it can be expected that between 10% and 15% of risk assessments could result in false positives that would allow the loan to go through. This margin of error would be considered significant risk that the company does not want to take on. The recommendation would be to reassess the data to identify if the customer parameters are appropriate to the model or not, or if there is data lacking; then re-conduct the training and testing of a new or adjusted model.
