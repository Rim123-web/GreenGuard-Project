GreenGuard is an intelligent mobile and web application designed to detect and diagnose plant diseases using Artificial Intelligence (AI).
By simply capturing or uploading a photo of a plant leaf, the app analyzes the image using a deep learning model trained on thousands of plant disease images and instantly determines whether the plant is healthy or infected.
### Backend — Django REST API + AI Model that is the folder GreenGuard-be-main
The backend is built with **Django** and **Django REST Framework**, responsible for:
- Handling HTTP requests from the frontend.
- Loading the trained **TensorFlow/Keras MobileNet** model.
- Performing image preprocessing and prediction.
- Returning JSON responses with classification results.

The backend was integrated with an AI model trained on plant disease datasets using **Keras** and **TensorFlow** on **Google Colab**.

### Frontend — Ionic + Angular that is the folder GreenGuard-main
The frontend is a hybrid mobile and web interface developed with **Ionic Angular**.  
It allows users to:
- Capture or upload plant images.
- View real-time AI analysis results.
- Access diagnosis history and status.
- Learn about detected diseases and possible treatments.
- Contact support or view project information.

---

##  Tools and Technologies

| Category | Tools Used | Description |
|-----------|-------------|-------------|
| **Backend** | Django, Django REST Framework | REST API and model integration |
| **AI / ML** | TensorFlow, Keras, MobileNet | Deep learning for image classification |
| **Frontend** | Ionic, Angular, TypeScript | Cross-platform UI and logic |
| **Development** | Visual Studio Code | IDE for frontend and backend |
| **Modeling** | Enterprise Architect | UML modeling (class) |
| **Data Science** | Kaggle, Google Colab | Dataset collection and model training |
| **Version Control** | Git, GitHub | Project versioning and collaboration |

---

##  Functionality

GreenGuard provides several key features:

###  1. Image Capture & Upload
Users can take or upload pictures of plant leaves directly from their device.

###  2. AI-Powered Classification
The backend model analyzes the image using deep learning and determines:
- Whether the plant is healthy or diseased.
- The type of disease (if detected).
- The model’s confidence level.

###  3. History and Tracking
The app keeps a record of past analyses, including date, status, and disease information.

###  4. Support & Information
A support section offers FAQs, details about the project, and university information.

---

##  Model Training

The deep learning model was developed through these steps:
1. **Dataset Preparation:** Image datasets of healthy and diseased leaves collected from Kaggle.  
2. **Preprocessing:** Image normalization, resizing, and augmentation.  
3. **Architecture:** Transfer learning using **MobileNetV2** for lightweight performance.  
4. **Training:** Done in Google Colab with GPU acceleration.  
5. **Evaluation:** Achieved high accuracy (91%) on test data.  
6. **Deployment:** Model integrated into the Django backend for real-time predictions.

---

##  User Interfaces

GreenGuard’s UI is designed for simplicity and usability, with four main sections:

1. **Home Page** – Search bar, plant list, and diagnosis history.  
2. **Review Page** – Preview uploaded images before analysis.  
3. **Consult Page** – Displays AI-generated results, disease info,Immediate diagnosis to provide feedback on the health status of plants.  
4. **Support Page** – FAQ, About Us, and About GreenGuard information.

---

##  Website and Commercialization

GreenGuard’s **website** serves as a promotional platform showcasing:
- App features and advantages.
- Contact and support options.
- Information about the collaboration with Ibn Tofail University.

---

## 🏛️ Academic Context

GreenGuard was created as part of an academic project in:
> **Intelligence Artificielle et Ingénierie de Données**  
> **Université Ibn Tofail**

This project demonstrates the practical integration of **machine learning, data engineering, and software development** in solving agricultural problems.

---


## Conclusion

GreenGuard combines the power of **Artificial Intelligence**, **Data Science**, and **Web/Mobile Engineering** to create an innovative tool for plant disease detection.  
By bridging AI and agriculture, GreenGuard contributes to more efficient, sustainable, and data-driven farming practices.


