## Hematovision : Advanced Blood Cell Classification Using Transfer Learning
HematoVision aims to develop an accurate and efficient model for classifying blood cells by employing transfer learning techniques. Utilizing a dataset of 12,000 annotated blood cell images, categorized into distinct classes such as eosinophils, lymphocytes, monocytes, and neutrophils.
## Team Details
| Field        | Information                            |
|--------------|----------------------------------------|
| Team ID      | LTVIP2026TMIDS65604                    |
| Team Size    | 4                                      | 
| Team Leader  | Thummala Seshugari Sarath Kumar Reddy  |
| Member 1     | Kathem Manasa                          |
| Member 2     | Bandela Pravallika                     |
| Member 3     | Thalla Indra Sreekar                   |
## [Project Demo Video Link]
<https://drive.google.com/file/d/1QxaNGZVuco2YtSQRfT5dQvEWWns71amL/view?usp=drivesdk>
## Technologies Used
| Category        | Technology            |
|-----------------|-----------------------|
| Programming     | Python                |
| Deep Learning   | TensorFlow, Keras     |
| Image Handling  | OpenCV, NumPy         |
| Web Framework   | Flask                 |
| Interface       | HTML, CSS             |
| Platform        | Google Colab          |
| Repository      | GitHub                |

## Project Setup

# 1. Clone the Repository- 
git clone <https://github.com/indra468/HematoVision-Advanced-Blood-Cell->

# 2. Create & Activate Virtual Environment
python -m venv .venv
# Linux / Mac
source .venv/bin/activate
# Windows
.venv\Scripts\activate

# 3.Install Dependencies
<pip install -r requirements.txt>
If requirements file is missing:
<pip install tensorflow keras numpy pandas matplotlib opencv-python flask>

# 4.Download Dataset
Link:  <https://www.kaggle.com/datasets/paultimothymooney/blood-cells/data>

# 5.Train the Model
<python train.py>
This will train the CNN model and save it as:
models/blood_cell_model.h5

# 6.Test the Model
<python predict.py>
This script loads the trained model and predicts the blood cell class for a sample image.

# 7.Run the Web Application
<python app.py>
Upload a blood cell image to get the *predicted cell type* instantly.
  
# 8.Expected Results
Accurate classification of 4 BC types
Fast prediction using trained CNN model
User-friendly web interface

# 9.Future Improvements
Add more blood disease detection
Improve accuracy using advanced architectures (ResNet, EfficientNet)
Deploy on cloud for real-time medical usage

# 10.License
This project is developed for *educational and research purposes*.
