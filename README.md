### Blind People Assist System

#### Overview
This system is designed to assist visually impaired individuals by integrating facial recognition, IoT-based sensory feedback, navigation, and voice interaction. It helps users identify people, navigate safely, recognize objects, and receive spoken descriptions of their surroundings.  

---

### Functional Modules & Their Details  

1. **Face Recognition & Access Control (des2.py)**  
   - Identifies known faces and grants access based on stored data.  
   - Helps users recognize familiar people in their surroundings.  

2. **IoT Camera & Servo Control (iot.py)**  
   - Captures images using a camera.  
   - Rotates a servo motor to scan different angles.  
   - Can detect obstacles and provide directional guidance.  

3. **Navigation System (nav.py)**  
   - Helps the user navigate using an intelligent guidance system.  
   - Uses camera input to detect pathways and obstacles.  
   - Provides voice-based directions for movement.  

4. **Memory Recall (ragf.py)**  
   - Remembers past interactions, objects, and places.  
   - Helps users recall previously identified objects or faces.  

5. **Image-to-Text & Summarization (read_books1.py)**  
   - Converts text from images (books, signs, documents) into readable text.  
   - Summarizes important content for the user.  
   - Reads out loud for better accessibility.  

6. **Surrounding Description (scence_desc.py)**  
   - Describes the environment using AI-based image analysis.  
   - Identifies objects, people, and their positions in the surroundings.  

7. **Sensory-Based Object Search (sensory_search.py)**  
   - Detects and identifies objects based on user input.  
   - Helps find specific items in the surroundings.  

8. **Emergency Alert System (sos.py)**  
   - Sends an emergency alert if the user needs help.  
   - Can notify a caretaker or emergency services.  

9. **Voice Interaction & Response (voice1.py)**  
   - Converts the user’s voice commands into text.  
   - Responds to queries in a natural voice.  
   - Can assist with information retrieval and navigation.  

---

### Installation & Setup  

#### 1. Install Dependencies  
Ensure you have Python installed. Then, install the required libraries:  

bash
pip install opencv-python numpy flask pytesseract pyttsx3 speechrecognition RPi.GPIO


#### 2. Install Tesseract OCR (For Text Recognition)  
Download and install Tesseract OCR:  
- *Windows*: [Download here](https://github.com/UB-Mannheim/tesseract/wiki)  
- *Linux (Ubuntu/Debian)*:  
  bash
  sudo apt install tesseract-ocr
  

#### 3. Clone the Repository (If applicable)  
bash
git clone https://github.com/your-repo/blind-assist.git
cd blind-assist


#### 4. Run the Main Script  
bash
python main.py


---

### Key Features  
✅ *Real-time Face & Object Recognition*  
✅ *AI-Based Scene Description*  
✅ *Hands-Free Voice Interaction*  
✅ *Text Extraction & Audio Summarization*  
✅ *Smart Navigation Assistance*  
✅ *Emergency SOS Alert System*  

---
