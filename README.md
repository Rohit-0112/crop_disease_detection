plant_webapp/
│
├── app.py                # Flask backend
├── model.py             # Model architecture
├── robust_model.pth     # Trained model file
│
├── templates/
│     └── index.html     # Webpage
│
├── static/              # Uploaded images & outputs


Requirements

Make sure Python (3.8+) is installed.

Install required libraries:
pip install flask torch torchvision timm pillow matplotlib opencv-python

▶️ How to Run

1. Open terminal inside the project folder:
cd plant_webapp


2. Run the Flask app:
python app.py


3. Open your browser and go to:
http://127.0.0.1:5000


How to Use??

1. Click **Choose File**
2. Upload a leaf image
3. Click **Predict**
4. View:

   * Predicted disease class
   * Uploaded image
   * Heatmap (if enabled)

*Ensure leaf images are present inside static folder
---
