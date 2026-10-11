# Create-a-binary-classification-model-for-a-loan-decision-app-deployed-in-Azure

## Aim of the project :
This project consists in :

- Creating a binary classfication model to predict if a client can get a loan or not to buy a house/apartment.
- Deploying the classification model in the cloud via an API.
- Creating a Web application deployed in the cloud so that it can be easy to get the output of the classification model for a none-technical person by clicking on the Predict box.

https://user-images.githubusercontent.com/124714195/221136751-edba765f-8dea-4616-9091-52c353865829.mov


## Walkthrough of the Web application :
- The input data are fed via a drop down menu by selecting the index of the client :
  <img width="1124" height="564" alt="236840897-59afab27-9316-4da5-97b8-fa450c46c41a" src="https://github.com/user-attachments/assets/d166763b-5666-4112-9a9b-14ffa3bf7606" />
- By clicking on the Explain prediction button, the user can explain to the client the features that explains the decision using a waterfall SHAP plot:
  <img width="1113" height="610" alt="236839768-16e70226-4e28-4e46-8500-399625cbee67" src="https://github.com/user-attachments/assets/aeee9098-daa7-4d72-b866-a87ef9d84cae" />
- Finally, by clicking on the Compare with other customers button, the user can illustrate to the client where the client position is compared to other clients based on a number of features, such as income, credit amount etc.
  <img width="850" height="508" alt="236842562-a0c197d5-6728-44d6-90f2-5c37203bc0bb" src="https://github.com/user-attachments/assets/49c1cea5-8bfa-4544-9b39-e25029f4c66e" />
