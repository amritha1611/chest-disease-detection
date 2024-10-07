# chest-disease-detection
Chest X-Ray classification is a critical task in medical imaging, aimed at 
identifying various thoracic diseases from radiographic images. This project 
introduces a deep learning model based on the DenseNet-121 architecture, 
tailored for the classification of 14 distinct chest conditions. The model leverages 
the ChestX-Ray14 dataset, comprising over 112,000 labelled images, to train and 
validate its performance.  
The model employs advanced techniques in deep learning and transfer learning 
to enhance its diagnostic accuracy. The model’s architecture is designed to 
capture intricate patterns in chest X-Rays, facilitating the detection of conditions 
such as pneumonia, fibrosis, and cardiomegaly. 
This project addresses the issue of class imbalance in the dataset by utilizing a 
customized weighted cross-entropy loss function, ensuring more accurate 
training across all classes. The model was trained using TensorFlow, with the 
training process significantly accelerated by the use of pre-trained weights and 
optimized with the Adam optimizer. 
