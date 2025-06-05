🌾 Crop Disease Detection Using Machine Learning
📌 Project Overview
This project uses Machine Learning techniques to detect diseases in crops from images. It focuses on a binary classification task—whether a crop is healthy or diseased.

🧠 Model Details
Algorithm Used: Support Vector Machine (SVM)

Frameworks: Scikit-learn, OpenCV

Preprocessing:

Image resizing

RGB conversion

Normalization

Label encoding with LabelEncoder

Data Split: 80% training / 20% testing

Model Saving: pickle used to save the trained model for future predictions

🎯 Accuracy
The model achieves an accuracy of 76% on the test dataset.

Accuracy may be impacted by:

Shadows or inconsistent lighting in images

Variation in image quality

🧪 Sample Testing
Two sample images (sample DF.JPG and sample DP.JPG) were used to test the final model, showing its practical application.

💻 GUI Support
The project includes a GUI created using Python (Tkinter) to:

Upload an image

Detect whether the crop is healthy or diseased using the saved model

Run the GUI:

bash
Copy
Edit
python "Diseases detection GUI.py"
📂 File Structure
main.ipynb - Main training and evaluation notebook

cnn_tourch.ipynb - Alternative deep learning model exploration

svm_model_crop.py - Contains the SVM training logic

Diseases detection GUI.py - GUI application to test the model

sample DF.JPG / sample DP.JPG - Sample testing images

README.md - Project documentation

🔧 How to Run
Clone the repository or unzip the project.

Install required libraries:

bash
Copy
Edit
pip install -r requirements.txt
Run training or directly use the saved model with the GUI.

📎 Dependencies
Python 3.x

OpenCV

scikit-learn

numpy

pickle

tkinter (for GUI)

📌 Future Improvements
Use deep learning (CNN) to improve accuracy

Add multi-class disease detection

Improve dataset qualit
