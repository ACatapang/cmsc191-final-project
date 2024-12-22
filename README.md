# Comparative Analysis of Different Image Generative Models Using Healthy Mango Leaf Dataset

This study conducts a comparative analysis of three image generative models—Autoencoders, Generative Adversarial Networks (GANs), and Restricted Boltzmann Machines (RBMs)—using a dataset of healthy mango leaf images. A subset of images underwent preprocessing, augmentation, and resizing to create a training set totaling to 1,620 images. The models were evaluated for their image generation under varying hyperparameters, epochs and batch sizes, and was quantitatively assessed using Mean Squared Error (MSE). Results highlight the strengths and limitations of each model, providing insights into their performance and suitability for image generation, with Autoencoders demonstrating the lowest MSE, while GANs and RBMs results suggests for the need of longer training time and advanced modifications to these implementations.

## Authors
- Andrei Joshua T. Gelaga [(atgelaga@up.edu.ph)](mailto:atgelaga@up.edu.ph)
- Angeline S. Catapang [(ascatapang@up.edu.ph)](mailto:ascatapang@up.edu.ph)
- Allen Christian P. Segovia [(apsegovia@up.edu.ph)](mailto:apsegovia@up.edu.ph)
- Jerico Luis A. Ungos [(jaungos@up.edu.ph)](mailto:jaungos@up.edu.ph)
- Justin Carl C. Sagun [(jcsagun@up.edu.ph)](mailto:jcsagun@up.edu.ph)
- Mark Henry S. Alcantara [(msalcantara4@up.edu.ph)](mailto:msalcantara4@up.edu.ph)
- Patrick John A. Francisco [(pafrancisco4@up.edu.ph)](mailto:pafrancisco4@up.edu.ph)
  
## Dataset and Colab Setup  

### 1. Upload the Dataset  
- Download the dataset from [this Google Drive folder](https://drive.google.com/drive/folders/1rImWvRnip90yi-SISY-NW6RVrtWPv1T0).  
- Upload all the files from the downloaded dataset to the folder path in your Google Shared Drive:  
  `/content/drive/Shareddrives/"CMSC 191"/"CMSC 191 GenAI Datasets"`  
- Ensure the uploaded folder contains approximately **1,600 files** and **1 class**.  

### 2. Copy the Colab Files  
- Open the notebooks available in [this Google Drive folder](https://drive.google.com/drive/folders/1Oup5-MJPrSVTLgEIYCa99RRq-F3en8Ot). Alternatively, the notebooks in this repository have google colab links attached.
- Create a copy of each `.ipynb` file to your Google Drive.  

### 3. Run the Colab Files
- Open the ipynb files in Google Colab.
- Ensure the dataset path corresponds to the correct Shared Drive folder: `"/content/drive/Shareddrives/"CMSC 191"/"CMSC 191 GenAI Datasets"`
- Run all cells in the notebook to process the dataset and execute the analysis.

---

Notes:
Ensure you have the necessary permissions for the Google Shared Drive.
Confirm that the dataset folder name matches exactly as stated to avoid path issues.





