# ENHANCED PLANT DISEASE DETECTOR
#### This project aims to recognize and classify plant diseases by analyzing leaf images. Two distinct models are trained using image data in different color formats: 
- **RGB Format** in `main.ipynb`, and its demo in `demo,ipynb`
- **HSV Format** in `HSV_main.ipynb`, and its demo in `HSV_demo.ipynb`
#### The primary goal is to maximize the accuracy of the models while comparing the performance of these color formats to determine which is more effective. Additionally, the project includes a feature to visually highlight the diseased areas on the leaves.

## Dataset: https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

## To run the code:
1. Install the latest versions of **Numpy, Matplotlib, Lime, Tensorflow, OS, and OpenCV.**
2. Download and unzip the dataset file from the given Kaggle link.
3. To run the main files, replace the `train_dir` with `{path of the data file in your PC}\color`, and run all the cells one by one. Please keep your PC connected to a constant power supply.
4. To run the demo files, please replace `dataset_path` with `train_dir` used in main files, and select any image from the dataset and replace `img_path` with its path.

## Data Preview:
![preview](https://github.com/user-attachments/assets/d8e628a1-69c4-4404-b6ab-3f39d53e32df)
Below is a comparison between RGB and HSV. HSV format makes the patterns and edges more recognizable.
![A comparison between RGB and HSV. HSV format makes the patterns and edges more recognizable.](https://github.com/user-attachments/assets/a3811387-859a-4628-909f-a4a5868c216c)

## Results:
The two models were trained with smooth convergence of both the graphs with minimal overfitting. The following are the graphs of the better performing RGB model from `main.py`.
![overfitting](https://github.com/user-attachments/assets/dd683bed-3873-41f4-8a9b-35ce59ee4aea)

The RGB can accurately predict the disease and the `lime` library worked successfully in highlighting the disese bearing parts of the leaves.
Demonstration of tracing out the disease on the leaf.
![Demonstration of tracing out the disease on the leaf.](https://github.com/user-attachments/assets/31fbeb85-f47f-4811-8b4e-c09be0f86f6d)
![Tomato_late_blight](https://github.com/user-attachments/assets/9f8653b5-477a-4e9c-b64f-82f64760d0c2)
![tomatolateblight](https://github.com/user-attachments/assets/0c9c80c7-6233-43d0-883b-27c6968f52e2)
