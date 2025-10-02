# Semester-AY-WorkshopName

This workshop is taught by XYZ (Position, Institution). Email: username@institution.edu

**Date**: Month DD, YYYY (e.g., September 16, 2025)

Checklist (⚠️ delete this section afterwards ⚠️)
---------------
- [ ] Upload/copy materials from the instructor. Make sure to attribute to the instructor's original repository if cloning, see example [here](https://github.com/barnardcsc/Fall-25-NASA-Space-Apps-2)
- [ ] Write repository description (On the right-hand side, click the settings icon next to **About**)
- [ ] Update `Workshop Description`: copy and paste from the event page (csc.barnard.edu) or the instructor's own description
- [ ] Update `Workshop Materials`: update the filetree, steps below:
  * Method 1 (recommended): ([Source](https://www.reddit.com/r/vscode/comments/1fmn6ye/made_a_vscode_extension_that_generate_a_file_tree/))

     * On VSCode, install the [File Tree Extractor](https://marketplace.visualstudio.com/items?itemName=Fuzionix.file-tree-extractor&ssr=false#overview) extension
     * Right-click on the root folder of the repository -> `Copy File Tree From This Directory`
  * Method 2: manually populate the file tree using the template below      

Workshop Description
---------------
*insert content here...*

Installation 
---------------
*modify/delete content here...*
Example:
**Option 1**: cloning the repository (preferred method)
Clone this repository
`git clone [insert git here]`

Note: If you do not know how to use git, you can directly click the code button on this page and then download the zipped directory.

Create a conda environment and jupyter notebook using the following command:
`conda create -n [your-env-name] python=3.13.5 numpy pandas matplotlib ipykernel jupyterlab`

Then remember to activate the environment [your-env-name] before starting a notebook, for example, with VSCode or jupyter lab.
`conda activate [your-env-name]`

**Option 2**: using [Google Colab](https://colab.research.google.com/)
1. Go to File > Open notebook.
2. Select Github.
3. Paste the repo url: *insert url*
4. Make sure you select workshop as the branch.
5. Open the notebook you would like to follow.
6. Make sure the following commands are copied:
```
from google.colab import drive
drive.mount('/content/drive')
```
You will log in to your drive and authenticate. Then, copy the notebook to your drive. You can then use the path `/content/drive/MyDrive/path/filename.csv`

Workshop Materials
---------------
This repository contains the following materials:

```bash
├── Dataset             # datasets
│   ├── 2022_Tcns.csv
│   ├── 2022_weather.csv
│   ├── 2023_NLDAS.csv
│   ├── 2023_Tcns.csv
│   ├── 2023_weather.csv
│   └── NLDAS_solar_weather_2023_Tcns.csv
└── Tutorials            # jupyter notebooks
    ├── 1_NLDAS_download.ipynb
    └── 2_RNN_RF_model.ipynb
```

If you have any questions or issues accessing files in the repository, please email csc@barnard.edu. If you have any questions about the workshop, please email the instructor.
