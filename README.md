# A Web Application for Fake Face Detection

### Project Overview
We are aiming to develop a web application for Real and Fake Face Detection utilizing either Flask or Streamlit, based on TensorFlow or PyTorch.

### Pipeline

1. **Dataset Collection**: Initially, we plan to reuse an open-source profile image dataset previously compiled from Kaggle and Twitter profiles (Seonghyeon, Jan 2019).

2. **Model Choice**: Our focus will be on leveraging a Convolutional Neural Network (CNN) for image classification. Specifically, we intend to start with a pretrained model, such as EfficientNet, and then fine-tune it.

3. **Training**: We will train our model using the Real and Fake Face Image dataset, ensuring a balanced representation of real and fake images.

4. **Evaluation**: The model's accuracy will be assessed and enhanced through fine-tuning and optimization. Benchmarking efforts may also be conducted to evaluate performance further.

5. **Deployment**: Once the model is adequately fine-tuned, we will employ Streamlit, a lightweight framework, to create a user-friendly application. This app will allow users to upload images to determine whether they are real or AI-generated. We might use GitHub Page as our web server.

### Tools and Libraries

- **TensorFlow** or **PyTorch** for the neural network framework.
- **ANTIALIAS** for image filtering.
- **OpenCV** for image processing.
- **NumPy** and **Pandas** for numerical and matrix operations.
- **Streamlit** for the web UI.
