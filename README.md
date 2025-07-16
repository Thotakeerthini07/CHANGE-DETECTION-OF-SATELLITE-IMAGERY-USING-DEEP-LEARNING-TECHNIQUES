# 🛰️ Change Detection in Satellite Imagery using Deep Learning

This project identifies and analyzes geographical and environmental changes between satellite image pairs using deep learning. It helps in applications like urban expansion tracking, deforestation detection, and disaster management.

## 🚀 Features
- Upload satellite image for automated change detection
- Visual output with highlighted changed areas (binary mask)
- Land vs Water area percentage analysis
- Deep Learning backend using U-Net model

## 🔍 Use Case Examples
- Urban planning and development
- Environmental monitoring
- Post-disaster area comparison
- Agricultural land use change

## 🧠 Technologies Used

| Component | Technology |
|----------|-------------|
| Frontend | HTML, CSS, JavaScript, Bootstrap |
| Backend | Python (Flask) |
| AI/ML | TensorFlow, Keras (U-Net) |
| Visualization | Matplotlib, PIL |
| Data Format | PNG, JPEG |
| Model | `satellite_unet.hdf5` |

## 🛠️ How It Works
1. Upload a satellite image.
2. Backend processes the image with a pretrained U-Net model.
3. The model returns a mask highlighting changed areas.
4. Outputs include:
   - Change mask image
   - Percentage of land and water

## 🧪 Installation and Run

```bash
git clone https://github.com/yourusername/change-detection-satellite.git
cd change-detection-satellite
pip install -r requirements.txt
python app.py
"# CHANGE-DETECTION-OF-SATELLITE-IMAGERY-USING-DEEP-LEARNING-TECHNIQUES" 
