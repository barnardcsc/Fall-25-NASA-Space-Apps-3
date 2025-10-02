#  Fall 25 How Machine Learning Can Help Us Estimate Crop Water Demand and Inform Irrigation Decisions

This workshop is taught by Jamie Duan (Postdoctoral Research Scientist at the Lamont-Doherty Earth Observatory of Columbia University).
Email: [jd4192@columbia.edu](mailto:jd4192@columbia.edu)

**Date**: October 1st, 2025

Workshop Description
---------------
(Repository partially cloned from [jamiemduan4192/Irrigation_AI](https://github.com/jamiemduan4192/Irrigation_AI))
​Precise irrigation is essential for sustainable agriculture, especially in arid and semi-arid regions. Determining when and how much water to apply is key to improving water use efficiency and supporting crop productivity. In this workshop, we will explore how various factors, including crop type, climate, and soil conditions, affect irrigation decisions, and how environmental monitoring tools can help guide these decisions. 

Participants will be introduced to different types of datasets commonly used in irrigation management, including plant sensor data, weather observations, and remote sensing imagery. We will discuss how machine learning can be used to integrate these diverse data sources and estimate crop water demand. The session will conclude with a hands-on activity to build a simple machine learning model for irrigation support.

Installation/Pre-workshop Instructions
---------------
### Initialize Google Earth Engine on your account
1. **Create your Google cloud project:** If you haven’t created a project, go to [Google cloud console](https://console.cloud.google.com/projectcreate) and create your project
2. **Go to the Google [Earth Engine cloud console](https://console.cloud.google.com/earth-engine/welcome)**
3. **Register your cloud project** Make sure the project name you created in step 1 is selected. Click “Register your Cloud project” under “Get Started” → 
4. **Register for noncommercial use:** Click “Get Started” under “See if you are eligible for noncommercial use” → answer questions
5. **Enable required APIs:** A window should pop-up, titled “Enable required APIs” → click “Enable”
6. **Initialize Earth Engine in your notebook:** in the code `ee.Initialize(project = "your-project")`, replace `your-project` with the project id you created in step 1

### Open Notebooks on Google Colab
Open the notebooks on [Google Colab](https://colab.research.google.com/)
1. Go to File > Open notebook.
2. Select Github.
3. Paste the repo url: `https://github.com/barnardcsc/Fall-25-NASA-Space-Apps-3`
4. Open the notebook you would like to follow.
5. Make sure the following commands are in the notebook:
	```
	from google.colab import drive
	drive.mount('/content/drive')
	```
	You will log in to your drive and authenticate. Then, copy the notebook to your drive. You can then use the path `/content/drive/MyDrive/path/filename.csv`

Workshop Materials
---------------
This repository contains the following materials:
```bash
.
├─ GEE_Irrigation/           # folder to upload to your google drive
│  ├─ 2022_Tcns.csv
│  ├─ 2022_weather.csv
│  ├─ 2023_Tcns.csv
│  └─ 2023_weather.csv
├─ Notebook-1-Exports/       # data you will create with 1_NLDAS_download.ipynb
│  ├─ 2023_NLDAS.csv
│  └─ NLDAS_solar_weather_2023_Tcns.csv
├─ Tutorials/                # python notebooks
│  ├─ 1_NLDAS_download.ipynb
│  └─ 2_RNN_RF_model.ipynb
└─ Irrigation AI.pdf         # workshop slides
```

If you have any questions or issues accessing files in the repository, please email csc@barnard.edu. If you have any questions about the workshop, please email the instructor.
