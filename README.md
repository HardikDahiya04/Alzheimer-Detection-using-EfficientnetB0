
Alzheimer’s MRI Classifier
A deep learning–powered web application for automated Alzheimer’s disease stage prediction from MRI scans. This project combines a fine-tuned EfficientNet model with a modern, interactive Flask web interface for clinical and research use.


•	User-friendly Web Interface: Drag-and-drop or click to upload MRI scans.
•	Real-time Prediction: Displays the predicted Alzheimer’s stage and model confidence.
•	Modern Dark Theme: Clean, accessible, and visually appealing design.
•	Robust Deep Learning Backend: EfficientNet model fine-tuned for MRI classification.
•	Secure and Local: All predictions run locally; no data leaves your machine.

Prerequisites
•	Python 3.8+
•	PyTorch
•	torchvision
•	Flask
•	Pillow
•	(Optionally) Google Colab for training

Install dependencies:
bash
pip install torch torchvision flask pillow
Folder Structure

Alzheimer_Final/
├── app.py
├── efficientnet_best.pth
├── static/
│   └── style.css
├── templates/
│   └── index.html


Usage
1.	Download or clone this repository.
2.	Place your trained model (efficientnet_best.pth) in the project root.
3.	Run the Flask app:
bash
python app.py
4.	Open your browser and go to http://127.0.0.1:5000.
5.	Upload an MRI scan and view the prediction and confidence.

   
Model Training
•	The EfficientNet model is trained on an Alzheimer’s MRI dataset with strong data augmentation and validation.
•	For training scripts and more details, see train.py or the Colab notebook (if provided).

Components
•	Web Interface: Allows users to upload MRI scans and displays predictions.
•	Animated Drag-and-Drop Area: Highlights the upload zone with an animated border and icon.
•	Prediction Display: Shows the predicted class (e.g., NonDemented) and confidence score.
•	Dark Theme: Ensures readability and a modern look.


Acknowledgments
•	PyTorch
•	Flask
•	EfficientNet
•	Original Alzheimer’s MRI Dataset
For questions or contributions, please open an issue or pull request.



