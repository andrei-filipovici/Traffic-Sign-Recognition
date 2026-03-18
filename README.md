# Traffic-Sign-Recognition
This project implements a model capable of recognizing 15 types of traffic signs from images and video streams. It simulates real-world conditions by approaching pictures with noise, lighting variations and different perspectives.
# Features
- Traffic sign classification (divided in 15 classes)
- Image preprocessing (augmentation, resize, normalization)
- Real-time video processing
- CNN based architecture
# Tools and Technologies
The project was developed in Jupyter Notebook environment using the following:
- Programming Language: Python
- Deep Learning Framework: PyTorch
- Computer Vision: OpenCV
- Data Visualization: Matplotlib
- Data Handling: NumPy/Tensors
# System architecture
This project follows a standard machine learning pipeline:
- Dataset Analysis: understanding the data, how it's distributed
- Preprocessing: data augmentation and normalization
- Modeling: creating the CNN architecture
- Training and Evaluation: training the model and evaluating the performances based on different indicators
# Results and future improvements
  In this project I was able to obtain 65% accuracy after 15 epochs and managed to get a good performance on identifying speed limit signs. Also the project has it's flaws which is best seen in the confusion between similar classes such as identifying the correct color of traffic lights.
  I plan to continue developing this project by:
- implementing a tracking system to mantain accurate predictions across multiple video frames
- expanding the dataset to include more scenarios
- deployment in real-world scenarios
