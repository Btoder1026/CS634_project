# Interpretable Gradient Boosting - Real Estate House Price Prediction

Ask a home buyer to describe their dream house, and they probably won’t begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition’s dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence. With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

# Milestone 1: (Week 1, 10 points)
Set up a development environment in your laptop. Learn the basics of docker by watching the following video:


If you are on Windows you will need to follow these instructions and install Docker Desktop and WSL2.

Independent of your OS, you may want to use VS Code IDE if you have no IDE experience before.

Submit the github repository URL with a branch titled ‘milestone-1’ with the README.md file containing the installation instructions you followed and a screenshot of your docker container terminal prompt. Add as collaborator the TA.

# In VSCode search Docker in the Extensions button and install Docker
<img width="1259" alt="Screenshot 2023-07-12 at 11 08 03 AM" src="https://github.com/Btoder1026/CS634_project/assets/131170660/e8197ccd-d1c1-4995-a938-54636615b45c">

# Download docker in Desktop
<img width="1426" alt="Screenshot 2023-07-12 at 11 12 37 AM" src="https://github.com/Btoder1026/CS634_project/assets/131170660/56630fe7-086a-46aa-9c25-c1d16d3e3445">

# In VSCode create a Dockerfile 
<img width="1130" alt="Screenshot 2023-07-12 at 11 20 53 AM" src="https://github.com/Btoder1026/CS634_project/assets/131170660/c1ae5cb6-a9ad-413c-8c2c-30438e6722f0">

# Bulid the Docker image and run the Docker container
<img width="1269" alt="Screenshot 2023-07-12 at 11 18 34 AM" src="https://github.com/Btoder1026/CS634_project/assets/131170660/021e0048-8a17-4e5f-98c7-e82c9f1eee32">

# Milestone 2: (Week 3, 40 points)
Download the dataset from 

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

Read the excellent summary on SHAP that Google engineers have put together. Watch the video and read the blog posts here to understand the problem and its solution provided by Tree SHAP. The blog post discusses the XGBoost implementation of gradient boosting but the concept is the same.

Perform the SHAP interpretation of the house price prediction model of your choice. At a minimum you should produce graphs that show the SHAP values for the features and the SHAP interaction values for these features.


# Milestone 3: (Week 4, 30 points)
Merge the earlier branch into the main branch and create a new branch titled ‘milestone-3. Do not delete the milestone-2 branch.

Repeat the analysis in Milestone 2 but this time use this or this guide to tune with Optuna the hyperparameters of the LightGBM model.

You need to creating a streamlit app for the house price prediction problem. Streamlit is a python library that allows you to create web apps with minimal coding and deploy them in the cloud. Deploy the streamlit app in HuggingFace streamlit spaces after you create a free account. The app must resemble this UI (please avoid the shown gif image) and in addition it must show a SHAP summary plot and a SHAP interaction plot.

Submit the github repository URL with a branch titled ‘milestone-3’ with the README.md file containing the link to the deployed HF space where the Milestone 2 calculation and the optimized app calculation price prediction can both be seen.

# Deploy the streamlit app in HuggingFace
https://huggingface.co/spaces/pichen/house-price-prediction



# Milestone 4: Documentation and Video Production (Week 5, 20 points)
Merge the earlier branch into the main branch and create a new branch titled ‘milestone-4’. Do not delete the milestone-3 branch.

Document extensively both the code as well as the results (10 points).

Use google sites to create a landing page for your app (5 points)

https://sites.google.com/njit.edu/house-price-prediction-pichen/home

Create a video that will demonstrate the app. The video should be no longer than 5 minutes and should be either uploaded to your youtube channel or inlcuded in the github repository as an mp4 (5 points).





