# Automated Vehicle Damage Detection System for Insurance Claims
In this project, I developed a machine learning system to automate vehicle damage detection using image data. Designed during an internship with Common Sense Software Solutions, the system leverages deep learning to streamline insurance claim evaluations by classifying damage types and improving assessment speed and reliability.

Key Features:
- Applied Convolutional Neural Networks (CNNs) for image-based classification of vehicle damage
- Processed input images to identify dents, scratches, and broken components using TensorFlow and OpenCV
- Integrated techniques from Scikit-learn and Keras for model training, validation, and calibration
- Achieved a model accuracy of 93.7% on real-world datasets, validating its applicability for insurers
- Aimed to reduce manual labor, costs, and human error in claim processing pipelines

Libraries & Frameworks:
- Python, TensorFlow, Keras, OpenCV, Scikit-learn, Pandas, NumPy, Seaborn, Matplotlib
- Algorithms: CNN, Logistic Regression, SVM, CalibratedClassifierCV
- Tools: ImageDataGenerator, ModelCheckpoint, EarlyStopping, Confusion Matrix, Precision/Recall Metrics

Future Goals:
- Adding a user-friendly GUI for faster uploads and visual interaction
- Supporting video-based damage detection in addition to images
- Including damage severity scores and estimated repair cost ranges
- Expanding dataset to include different car types and damage conditions
- Integrating the model with real-time insurance claim systems via API

Use Case:
The model enables insurers to automate claim initiation by identifying damage types and assessing severity. This speeds up the process, minimizes manual inspection time, and helps in building trust with policyholders by increasing objectivity and response time.
