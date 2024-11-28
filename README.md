
# **Nepali OCR**  
**An AI-Powered Optical Character Recognition (OCR) System for Nepali Handwritten and Printed Text**

## **Introduction**
Nepali OCR is a machine learning-powered tool designed to digitize handwritten and printed Nepali text from images. Built using Flask for the backend, the system leverages convolutional neural networks (CNNs) and Tesseract OCR for accurate recognition and conversion. This project aims to address the lack of tools for Nepali text digitization, making it easier to process and analyze documents in Nepali script.

---

## **Features**
- **Handwritten Text Recognition:** Recognizes Nepali handwriting from uploaded images and converts it to digital text.
- **Printed Text Analysis:** Processes printed Nepali documents for digitization.
- **User-Friendly Interface:** Web-based interface for easy interaction, built with HTML, CSS, and JavaScript.
- **AI-Driven:** Utilizes CNN models for accurate character recognition.
- **Export Options:** Allows users to save extracted text in multiple formats (e.g., `.txt`, `.docx`).
- **Preprocessing:** Includes noise reduction and image enhancement for better accuracy.

---

## **Technology Stack**
- **Backend:** Flask (Python)  
- **Frontend:** HTML, CSS, JavaScript  
- **Machine Learning:** Convolutional Neural Networks (TensorFlow/Keras)   
- **Tools:** OpenCV for image preprocessing  

---

## **Installation Instructions**
1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/nepali-ocr.git
   cd nepali-ocr
   ```

2. **Set Up the Environment**  
   Install the required dependencies using `pip`:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**  
   Start the Flask development server:  
   ```bash
   python app.py
   ```

4. **Access the Application**  
   Open a web browser and go to:  
   ```
   http://127.0.0.1:5000
   ```

---

## **Usage**
1. Upload an image containing handwritten or printed Nepali text.  
2. Click on the **"Analyze"** button to process the image.  
3. View the extracted text in the result box.  
4. Optionally, download the extracted text or copy it for further use.

---

## **System Workflow**
1. **Image Preprocessing:**  
   - Noise removal, thresholding, and resizing using OpenCV.  
2. **Text Recognition:**  
   - Handwriting: CNN-based character recognition model.  
   - Printed Text: Tesseract OCR engine.  
3. **Postprocessing:**  
   - Text cleaning and formatting for better usability.  

---

## **Screenshots**
**1. Home Page**  
![Home Page](static\images\homepage.jpg)  

**2. Image Upload**  
![Image Upload](static\images\letterpage.jpg)  

**3. Extracted Text**  
![Extracted Text](static\images\wordupload.jpg)  

---

## **Contributing**
We welcome contributions to enhance the features and performance of Nepali OCR.  
1. Fork the repository.  
2. Create a new branch (`feature/your-feature-name`).  
3. Submit a pull request.

---

## **Future Enhancements**
- **Real-Time Camera Input:** Integrate support for live image capture.
- **Improved Handwriting Recognition:** Enhance accuracy for complex and varied handwriting styles.  
- **Language Extension:** Add support for other regional languages.  

---

## **License**
This project is licensed under the [MIT License](LICENSE).

---

## **Acknowledgments**
- **Tesseract OCR** for text recognition.  
- **TensorFlow/Keras** for the machine learning model.  
- Nepali script datasets and contributors for model training.

---
