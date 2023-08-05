# Railway Track Fault Detection Project

<b>GOAL</b>

To predict railway track faults.

In this project, I used Python and TensorFlow to classify images.

<b>DATASET</B>

Dataset used: https://www.kaggle.com/salmaneunus/railway-track-fault-detection

# Railway Track Fault Detection Project

This GitHub repository contains a Python project focused on developing an automated system for detecting faults in railway tracks using computer vision and machine learning techniques. The project aims to enhance safety and efficiency by identifying potential issues such as cracks, misalignments, or defects in real-time.

## Steps to Use the Project

1. **Clone the Repository**: Clone this repository to your local machine using the following command:
   
   ```
   git clone https://github.com/your-username/railway-track-fault-detection.git
   ```

2. **Navigate to the Project Directory**: Move into the project directory:
   
   ```
   cd railway-track-fault-detection
   ```

3. **Set Up Environment**: Install the required Python packages by running the following command:

   ```
   pip install -r requirements.txt
   ```

4. **Download and Preprocess the Dataset**: Download the railway track fault detection dataset from Kaggle. Make sure you have a Kaggle account and API key. Replace `your-username` and `your-api-key` in the command below with your actual Kaggle credentials:

   ```
   kaggle datasets download -d salmaneunus/railway-track-fault-detection -p dataset/
   unzip dataset/railway-track-fault-detection.zip -d dataset/
   ```

5. **Explore the Jupyter Notebook**: Open the Jupyter notebook named `railway_track_fault_detection.ipynb` to understand the project implementation and execution steps. This notebook provides a detailed guide on loading the dataset, building and training the deep learning model, evaluating performance, and testing the model on sample images.

6. **Results and Conclusion**: The project utilizes a pre-trained InceptionV3 model for feature extraction and classification. The training and validation accuracy and loss are visualized using plots to assess the model's performance during training. The final trained model is capable of classifying railway track images as either defective or non-defective.

7. **Contact Information**: For any questions or inquiries, you can reach out to durgeshkumar.nitraipur@gmail.com

Please note that the actual code and detailed steps are available in the Jupyter notebook. This summary provides an overview of the project and the steps to use it.
