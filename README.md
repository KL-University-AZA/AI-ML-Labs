# AI-ML-Labs
KLH AZIZ NAGAR AI ML LAB'S

# Augmented Image and Video Processing Pipeline with Meta SAM 2 and YOLO Models

This project establishes a robust workflow for augmenting images and videos, integrating the Meta SAM 2 model for mask creation and two YOLO models for object recognition. It offers diverse augmentation techniques such as pixelation, hue adjustment, mask swapping, and glowing effects. The system also enables generative AI-powered transformations through the Stability AI API.

Key Features
Meta SAM 2 Model:

Executes mask generation and propagates masks across frames.
YOLO Object Detection Models:

Custom YOLO Model:
User-trainable with built-in data augmentation.
Pretrained YOLO Model:
Instantly detects objects with minimal input.
Manual Data Input:

Users can bypass the YOLO models and manually provide frame numbers and object coordinates.
Image Annotator Tool:

Generates YOLO-compatible .txt annotations to simplify custom model training.
Augmentation Capabilities
Masking: Creates masks for objects from either YOLO detection or manual input.
Inverse Masking: Masks everything except the detected object.
Pixelation: Blurs the masked area using pixelation.
Hue Adjustment: Alters the hue of selected areas.
Mask Swapping: Replaces the mask with new content (image/video).
Glow Effect: Adds a glowing outline around the masked object.
Image-to-Image Transformation: Applies generative AI models from Stability AI to enhance masked regions.
YOLO Models Overview
Trainable YOLO Model:

Customizable with user-provided datasets and built-in augmentation techniques.
Pretrained YOLO Model:

Detects objects using only the object name as input.
Provides frame numbers and coordinates to be processed by the SAM 2 model.
Manual Input Handling
Users can directly input frame numbers and object coordinates instead of relying on YOLO models.
These inputs integrate with the SAM 2 model for further processing.
Meta SAM 2 Operations Summary
Masking & Inverse Masking: Detects objects or their surroundings.
Pixelation & Hue Change: Alters visual properties of masked areas.
Mask Replacement & Glow Effect: Enhances masked areas with creative visuals.
Generative AI Transformations: Uses Stability AI’s models for seamless object transformation.
Image Annotator Tool
Provides an easy way to generate YOLO-compatible annotations for custom object detection models.
Supports manual labeling to streamline the model training process.
Deployment
Application Platform: Hosted as a Streamlit app on Hugging Face Spaces.
Hugging Face URL: Link to live deployment.
Model URL: Access to the SAM 2 model.
Video URL: Demonstration videos of the deployment.
Usage Instructions
Train a custom YOLO model or use the pretrained one.
Optionally, input frame numbers and object coordinates manually.
Use the Image Annotator for generating custom annotations.
Run the augmentation pipeline with the SAM 2 model to apply desired transformations.
