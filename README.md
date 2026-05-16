# Automated-Retinopathy-Diagnosis-System-with-Real-Time-Image-Processing
Final year project focused on diabetic retinopathy diagnosis using deep learning, image processing, and real-time retinal image analysis.
🩺 Automated Diabetic Retinopathy Diagnosis System An AI-Driven, Portable, and Cost-Effective Healthcare Solution 📌 Abstract

Diabetic Retinopathy (DR) is one of the leading causes of preventable blindness worldwide, affecting millions of diabetic patients every year. Early detection is critical, yet access to expert ophthalmologists and expensive retinal imaging equipment remains limited, especially in rural and low-resource regions.

This project presents a complete end-to-end Automated Diabetic Retinopathy Diagnosis System, integrating hardware, mobile technology, deep learning, cloud deployment, and an AI-assisted decision support system. The proposed solution is portable, affordable, and intelligent, enabling early screening and supporting healthcare professionals in diagnosis.

🎯 Problem Statement

Diabetic Retinopathy progresses silently and is often detected too late

Lack of specialist doctors in rural and underserved areas

Retinal imaging systems are expensive and non-portable

Manual diagnosis is time-consuming and subjective

✅ Proposed Solution

This project solves the above challenges by introducing:

📱 **Smartphone-based retinal imaging

🔍 AI-powered deep learning diagnosis

☁️ Cloud-deployed model for scalability

🤖 AI Bot assistance for decision support

💰 Low-cost and portable healthcare system**

The system enables early detection, fast screening, and scalable deployment, contributing directly to the global healthcare sector.

🧠 System Overview 🔗 End-to-End Workflow

A 30-diopter lens integrated with a smartphone captures retinal images

Images are sent to a cloud-hosted deep learning model

A CNN-based AI model analyzes the retina image

The system predicts the stage of diabetic retinopathy

Results are returned to the application with AI-assisted recommendations

Final medical decisions remain with qualified professionals

🏗️** System Architecture**

Hardware → Mobile App → Cloud AI Model → AI Bot → User/Doctor Interface

Hardware Layer: Smartphone + 30D lens

Software Layer: Mobile app + web interface

AI Layer: CNN-based deep learning model

Cloud Layer: Model deployment & inference

Ethical Layer: AI assistance, not replacement of doctors

🧪 AI Model & Methodology 📊 Dataset

**Fundus (retinal) images

Multi-class labels:

Normal

Mild DR

Moderate DR

Severe DR

Proliferative DR

🧠 Model**

Convolutional Neural Network (CNN)

Input size: 224×224 retina images

Data preprocessing:

Resizing

Normalization

Augmentation

Training & evaluation using real medical images

📈 Performance

Achieved promising accuracy on limited dataset

Model shows strong potential for further improvement with larger datasets

🧰 Technologies Used 🔹 Programming & Frameworks

Python ** TensorFlow / Keras

Scikit-learn**

🔹** Data & Visualization

NumPy, Pandas

Matplotlib, Seaborn, Plotly

🔹 Deployment & Interface

Streamlit (Web App)

Cloud deployment (API-based inference)

🔹 Hardware

Smartphone

30-Diopter Lens (Fundus imaging)**

📂 Repository Structure 📁 data # Retinal image datasets 📁 notebooks # Model training and experimentation 📁 models # Trained CNN models 📁 results # Evaluation metrics and visualizations 📁 app # Web / mobile interface code 📄 README.md # Project documentation 📄 requirements.txt # Required libraries

🧠** Ethical Considerations**

The system does NOT replace doctors

AI results are advisory only

Final diagnosis must be performed by qualified medical professionals

Designed to assist, not automate medical decisions

🌍 Impact on Society & Healthcare

🩺 **Early detection of diabetic retinopathy

🌍 Improved healthcare access in rural regions

💸 Reduced screening costs

⏱️ Faster diagnosis and screening

📊 Data-driven medical support**

This project contributes to preventing avoidable blindness and supports public health initiatives worldwide.

🔮 Future Scope & Research Opportunities

Training on larger and multi-center datasets

Integration of advanced deep learning models:

Vision Transformers (ViT)

Attention-based CNNs

Multi-modal learning

Real-time deployment on edge devices

Explainable AI (XAI) for medical transparency

Expansion to detect other retinal diseases

🧑‍🎓 Academic Contribution

This project demonstrates:

**Applied deep learning in healthcare

Integration of hardware + software + AI

Research-oriented system design

Strong foundation for future postgraduate research**

👤 Author

Abdul Siddique Final Year Project (FYP / Thesis) Computer Science Student fall 21-25 
