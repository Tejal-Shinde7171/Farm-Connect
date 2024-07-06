# Farm-Connect Classifier 🌿
#### A simple ML and DL based website which recommends the best crop to grow, fertilizers to use and the diseases caught by your crops.

# DISCLAIMER ⚠️
#### This is a POC(Proof of concept) kind-of project. The data used here comes up with no guarantee from the creator. So, don't use it for making farming decisions. If you do so, the creator is not responsible for anything. However, this project presents the idea that how we can use ML/DL into precision farming if developed at large scale and with authentic and verified data.

# MOTIVATION 💪
#### - Farming is one of the major sectors that influences a country’s economic growth. 
#### - In country like India, majority of the population is dependent on agriculture for their livelihood. Many new technologies, such as Machine Learning and Deep Learning, are being implemented into agriculture so that it is easier for farmers to grow and maximize their yield. 
#### - In this project, I present a website in which the following applications are implemented; Crop recommendation, Fertilizer recommendation  respectively. 
#### - In the crop recommendation application, the user can provide the soil data from their side and the application will predict which crop should the user grow. 
#### - For the fertilizer recommendation application, the user can input the soil data and the type of crop they are growing, and the application will predict what the soil lacks or has excess of and will recommend improvements. 

# How to run locally 🛠️
  #### - Before the following steps make sure you have [git](https://git-scm.com/download), [Anaconda](https://www.anaconda.com/) or [miniconda](https://docs.conda.io/en/latest/miniconda.html) installed on your 
         system
 
  #### - deploy` branch has only the code required for deploying the app (rest of the code that was used for training the models, data preparation can be accessed on `master` branch)
  #### - It is highly recommended to clone the deploy branch for running the project locally (the further steps apply only if you have the deploy branch cloned)
  #### - Once the project is cloned, open anaconda prompt in the directory where the project was cloned and paste the following block
   ### conda create -n Farm Connect python=3.6.12
   ### conda activate Farm Connect
   ### pip install -r requirements.txt
   ### - And finally run the project with
   ###  python app.py
  # Open the localhost url provided after running `app.py` and now you can use the project locally in your web browser.

# Further Improvements 📈
  ## This was my first big project so there are lot of things to improve upon
#### - CSS code is totally messed up :pensive
#### - Frontend can be made more nicer 
#### - More data can be collected manually via web scrapping to make the system more accurate 
#### - Additional plant images can be collected to make the disease detection part more robust and generalized
#### - Modularized code can be written instead of writing in Jupyter Notebooks 
# Contact 📞

#### If you have any doubt or want to contribute feel free to email me or hit me up on [LinkedIn]
###[ linkedin.com/in/tejal-shinde-51550b2b6](https://www.linkedin.com/in/tejal-shinde-51550b2b6/)












  
