# Geologist_AI

An AI-powered tool that analyzes drill core images to identify rock types using computer vision and machine learning.

##  Features

- **Computer Vision**: Analyzes rock textures and colors using ResNet-18
- **Unsupervised Learning**: Clusters similar rock samples automatically
- **Web Interface**: User-friendly Gradio app for real-time analysis
- **Industry Application**: Solves real geological logging challenges

## How to Use

1. Upload a drill core image
2. Click "Analyze Core Sample"
3. Get instant rock type classification

## Technical Approach

- **Feature Extraction**: ResNet-18 CNN pre-trained on ImageNet
- **Clustering**: K-Means with PCA dimensionality reduction
- **Classification**: Rule-based with color analysis
- **Deployment**: Gradio web interface

## Supported Rock Types

- Gold-bearing rock
- Iron-rich rock
- Lithium-rich rock
- Copper-bearing rock
- Quartz-rich rock
- Waste rock

##  Development
Built with Python, PyTorch, Scikit-learn, and Gradio.
