# Classification of Uveitis using CNN anf Random Forest Classifier

The problem addressed in this project is the accurate and efficient
classification of various eye diseases using fundus images. Manual
diagnosis and classification of eye diseases can be time-consuming,
subjective, and prone to errors. Automating this process can greatly benefit
healthcare professionals, enabling early detection and timely intervention,
leading to improved patient outcomes. However,the challenge lies in
developing a robust and reliable classification model that can accurately
identify different eye diseases based on fundus images.
Traditional approaches to eye disease classification often rely on
handcrafted features and traditional machine learning algorithms, which
may struggle to capture complex patterns and variations in fundus images.
Deep learning methods, such as Convolutional Neural Networks (CNN),
have shown promising results in image classification tasks. However, they
may lack interpretability, which is crucial in medical applications.

A suitable approach that combines the strengths of CNN for feature extraction and the
interpretability ofRandom Forest algorithm to develop a hybrid model for
eye disease classification. The goal is to create an accurate and
interpretable model that can reliably classify retinal images into different
disease categories, ultimately aiding healthcare professionals in making
informed decisions and improving patient care.

CNNs extract informative features from ocular images, while Random Forests provide
interpretable results and handle complex relationships in the feature space.
This integration enables improved accuracy in uveitis classification,
enhances the understanding of the key features contributing to
classification decisions, and aids in clinical decision support.

 A diverse dataset of ocular images or relevant clinical data from patients diagnosed with uveitis
subtypes. The dataset will be annotated and divided into training,
validation, and test sets. We will pre-process the data, including image
resizing, normalization, and feature extraction. Data augmentation
techniques will be employed to increase the diversity of the training data.
The CNN component of the model will be trained to learn relevant features
from the ocular images. The trained CNN will extract features, which will
then be fed into the Random Forest model for further classification. The
Random Forest model will leverage decision trees to capture complex
relationships among the extracted features and make predictions on the
uveitis subtypes.
## Fundus Dataset
![download](https://github.com/gangakona/Classification-of-Uveitis-using-CNN-and-Random-Forest-Classifier/assets/110378442/94e2754d-3a2c-495c-a018-99704fd82371)

