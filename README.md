# 🧠 Brain Tumor Detection with Convolutional Neural Network (CNN)

# 🔗 GitHub Repository: https://github.com/Bayu-Prasetyo0301/Brain-Tumor-Detections-With-CNN.git

# 📌 Overview
Brain Tumor Detection with CNN adalah proyek Deep Learning yang bertujuan untuk mengklasifikasikan citra MRI otak ke dalam dua kategori: Tumor dan Non-Tumor. Model ini menggunakan arsitektur Convolutional Neural Network (CNN) untuk mengenali pola visual dari citra dan melakukan klasifikasi otomatis, membantu dalam proses diagnosis medis secara cepat dan akurat.

# ⚙️ Project Workflow

# 🗂️ Dataset Preparation
📁 Citra MRI dikumpulkan dan diklasifikasikan ke dalam dua kelas: tumor detected dan no tumor detected.

🧮 Citra diubah ke format array dan dilabeli secara biner (0 = non-tumor, 1 = tumor).

# 🔀 Dataset dibagi menjadi:

🏋️ Training Set: 80%

🧪 Validation Set

🧭 Test Set: 20%

# 🧠 Model Architecture (CNN)

📦 CNN terdiri dari beberapa blok:

Conv2D ➝ ReLU ➝ MaxPooling2D

# 🧱 Diikuti oleh:

Flatten ➝ Dense ➝ Dropout (untuk regularisasi)

# 🎯 Output layer:

Menggunakan sigmoid untuk klasifikasi biner

# 🏃‍♂️ Training and Evaluation
⚙️ Model dilatih dengan:

- Loss: binary_crossentropy

- Optimizer: Adam

📊 Validasi di setiap epoch untuk memantau overfitting

# 📈 Visualization

![image](https://github.com/user-attachments/assets/c0a38efe-44fe-4c0f-9cef-fdfcc2d54882)

![image](https://github.com/user-attachments/assets/6576f6be-4a92-4371-841d-dfe801115bab)

![image](https://github.com/user-attachments/assets/d4b14067-5689-4f5b-bc5f-cdd97d858007)

# 🧠 Tech Stack & Libraries

<img src="https://www.tensorflow.org/images/tf_logo_social.png" alt="TensorFlow" width="30"/>

<img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" alt="Pandas" width="30"/>

<img src="https://matplotlib.org/_static/logo2_compressed.svg" alt="Matplotlib" width="30"/>

<img src="https://seeklogo.com/images/O/opencv-logo-61F1E4B889-seeklogo.com.png" alt="OpenCV" width="30"/>

<img src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" alt="Scikit-learn" width="30"/>

<img src="https://upload.wikimedia.org/wikipedia/commons/0/06/PIL_logo.svg" alt="PIL" width="30"/>

<img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="Colab" width="30"/>

# HASIL

