🎨 Doodle Drawing Recognition Using CNN

This project recognizes hand-drawn doodle sketches using a Convolutional Neural Network (CNN) and Google’s Quick Draw Dataset. Draw on the live canvas, and the model predicts your doodle!

🚀 Overview

Dataset: Google Quick Draw Dataset. Download some .npy files available at https://console.cloud.google.com/storage/browser/quickdraw_dataset/full/numpy_bitmap;tab=objectsinv=1&invt=AbkXnw&prefix=&forceOnObjectsSortingFiltering=false

Backend: Flask

Frontend: HTML, CSS, JS with a live canvas for sketch input

🛠️ How It Works

  1. Draw a doodle on the canvas.

  2. The Flask backend processes the sketch using the CNN model.

  3. The predicted class is displayed instantly.

📝 Steps to Run

1. Clone the Repository

    git clone https://github.com/yourusername/doodle_recognition.git

    cd doodle_recognition
  
2. Run the Flask Backend

    Ensure Flask and TensorFlow are installed.

    python app.py (or) flask run

3. Open the Web App
   
    Navigate to:
    http://127.0.0.1:5000


Start Drawing! 🎨
