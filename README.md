# Dog Breed Identification App 

This is a Streamlit web app that identifies dog breeds from images using a pre-trained TensorFlow model based on ResNet50.  
You can upload an image from your local device or provide an image URL, and the app predicts the dog's breed with confidence scores and shows you the result along with a link to learn more.

---

## Features

- Upload an image file or input an image URL
- Uses a deep learning model trained on 120 dog breeds
- Displays the predicted breed with confidence
- Shows the uploaded image with the predicted breed
- Download the result image with the breed and confidence overlaid
- Link to Wikipedia for more info about the breed
- Simple and clean Streamlit UI

---

# How It Works

# Model Loading
Loads a ResNet50-based Keras model trained to classify dog breeds.

# Image Input
Accepts an image input (upload or URL), preprocesses it to 224×224 pixels.

# Prediction
Predicts the breed class with confidence.

# Output
Displays results and allows downloading annotated image.
