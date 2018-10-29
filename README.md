
## Machine Learning Engineer Nanodegree

Capstone project for Udacity MLND

### Image recognition to detect multiple attributes using Machine Learning

---

### System used:

Windows 10 Machine with 2.9 GHz Intel Core i7, 16GB RAM, 2GB NVIDIA GeForce GTX 950M

---

### Software and libraries used:

- Python 3.6 - Anaconda Distribution

- To run tensorflow on GPU: [https://www.tensorflow.org/install/install_windows](https://www.tensorflow.org/install/install_windows)
    - CUDA® Toolkit 9.0.
    - cuDNN v7.0.

- Main Libraries:

    - pandas
    - numpy
    - tensorflow-gpu 1.8.0 --> conda install -c anaconda tensorflow-gpu
    - keras-gpu 2.2.0 --> conda install -c anaconda keras-gpu

---

### Dataset

 The dataset for this project is 1.44 GB and it is available on Kaggle:
 
[https://www.kaggle.com/jessicali9530/celeba-dataset](https://www.kaggle.com/jessicali9530/celeba-dataset)


---

### Instructions

The shared link contains all the required documents to run the project, except for the Data Set, which is too large to uploaded in the submition.

In order to replicate the project, the data set have to be downloaded from [https://www.kaggle.com/jessicali9530/celeba-dataset](https://www.kaggle.com/jessicali9530/celeba-dataset) and stored in the "capstone_project" folder.

Initially this folder will look like this:

```bash
├── 1.\ Capstone\ Project\ -\ Image\ Recognition.ipynb
├── 2.\ Benchmark\ Comparison.ipynb
├── 3.\ Predict.ipynb
├── Capstone\ Project.docx
├── haarcascades
│   ├── haarcascade_frontalface_alt.xml
│   └── haarcascade_smile.xml
├── icons
│   ├── boy-2.png
│   ├── couple-2.png
│   ├── elderly-2.png
│   ├── serious-2.png
│   ├── smiling-2.png
│   └── woman-2.png
├── non_celeba_pics
│   ├── 001.jpg
│   ├── 002.jpg
│   ├── 003.png
│   └── hidethepainharold.jpg
├── proposal
│   ├── MLND_capstone_proposal.docx
│   ├── MLND_capstone_proposal.pdf
│   ├── README.md
│   ├── Untitled.ipynb
│   ├── capstone_proposal.zip
│   └── ~$ND_capstone_proposal.docx
└── saved_models
    ├── gender_model.h5
    ├── smile_model.h5
    └── young_model.h5
```

then the "celeba-dataset" folder with the data set have to be added.

- Important Files:
    - 1. Capstone Project - Image Recognition.ipynb
        Run all the models
    - 2. Benchmark Comparison.ipynb
        Compare the craeted model with the benchmark
    - 3. Predict.ipynb
        Run predictions using the developed models. Takes images filenames as input


Due file sizes, it is not possible to upload all the required files.
Please feel free to contact me if you want details about how to run this project.
