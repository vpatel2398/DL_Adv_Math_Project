# DL_Adv_Math_Project_final

## Project members:
1. Yash Suresh Upadhyay -101378657
2. Vivek Patel - 101432083
3. Vishal Patel - 101446059
4. Hetvi Shah - 101439231

## Project Glasscheck:
is a computer vision and deep learning practice that aims to identify and classify humans in images or videos based on whether they are wearing glasses or not.

## Description:

The system takes an input image or video frame as its input and utilizes advanced computer vision algorithms and deep learning models to analyze the visual features of human faces present in the scene. It focuses on detecting the presence of eyeglasses on the faces of individuals.

## The process involves several key steps:

**Face Detection**: The system first identifies and localizes human faces in the input image or frame using a face detection algorithm.

**Facial Landmark Detection**: Once the human faces are detected, the system performs facial landmark detection to identify key points on the face, such as the position of the eyes, nose, and mouth. This helps in precisely localizing the regions of interest, such as the eye area where eyeglasses are usually present.

**Glasses Detection**: The system then uses a trained deep learning model to classify the detected regions of interest as either "glasses" or "no glasses." Convolutional Neural Networks (CNNs) and other deep learning architectures were used for this task. The model is trained on a large dataset of labeled images with examples of individuals wearing glasses and those without glasses.

**Output and Visualization**: Finally, the system provides the results as output, indicating whether each detected human face is wearing glasses or not. This information is visualized by drawing bounding boxes around the faces or using labels to indicate "glasses" or "no glasses" next to each face in the image.

## Applications:

The Glasses/No Glasses Detection system has various practical applications, including:

**Human-Computer Interaction**: In human-computer interaction systems, detecting whether a person is wearing glasses can help tailor the user interface or adjust the display settings to accommodate users with glasses effectively.

**Surveillance and Security**: In surveillance systems, detecting individuals with glasses can be useful for identifying specific individuals in security footage and tracking their movements.

**Augmented Reality (AR)**: In AR applications, detecting glasses can aid in rendering virtual objects more realistically by considering the user's real-world appearance.

**Retail and Advertising**: In retail and advertising, the system can provide insights into consumer preferences and help design targeted advertising campaigns based on whether individuals wear glasses or not.

Overall, the Glasses/No Glasses Detection system contributes to various domains, enhancing human-centric applications and providing valuable information for decision-making in diverse scenarios.
