--

# Gesture and Voice Control System  

A robust system that leverages **Azure Cognitive Services** for speech recognition and **MediaPipe** for gesture recognition, enabling intuitive voice commands and hand gesture controls.  

## Features  

- 🎤 **Voice Commands**: Open and close applications using speech recognition.  
- 🖐️ **Gesture Recognition**: Control the mouse cursor and perform clicks with hand gestures.  
- 🖥️ **User-Friendly GUI**: Includes a **Tkinter-based control panel** to start and stop speech and gesture recognition.  

---

## Prerequisites  

Ensure the following tools and libraries are installed:  
- **Python 3.9** or higher  
- Azure Cognitive Services Speech SDK  
- MediaPipe  
- OpenCV  
- PyAutoGUI  
- Tkinter  

---

## Installation  

### 1. Clone the Repository  
```bash  
git clone https://github.com/jagdeeshjk/Hand_control.git 
cd Hand_control  
```  

### 2. Create a Virtual Environment  
```bash  
# On Windows  
python -m venv myenv  
source myenv/Scripts/activate  

# On macOS/Linux  
python -m venv myenv  
source myenv/bin/activate  
```  

### 3. Install Dependencies  
```bash  
pip install -r requirements.txt  
```  

### 4. Configure Azure Cognitive Services  
1. Create an Azure Cognitive Services account.  
2. Obtain your Speech API Key and Region.  
3. Replace placeholders `YOUR-SPEECH-API-KEY` and `YOUR-LOCATION` in the following files:  
   - `APP.py`  
   - `test_def.py`  

---

## Usage  

### Run the Main Application  
```bash  
python APP.py  
```  

### Run the GUI Application  
```bash  
python App1.py  
```  

### Run the Test Script  
```bash  
python test_def.py  
```  

---

## Project Structure  

- `APP.py` - Main script for gesture and voice control.  
- `App1.py` - GUI-based application for gesture and voice control.  
- `test_def.py` - Script to test speech recognition functionality.  
- `requirements.txt` - List of dependencies.  

---

## Acknowledgments  

This project uses the following amazing tools and technologies:  
- [Azure Cognitive Services](https://azure.microsoft.com/en-us/services/cognitive-services/)  
- [MediaPipe](https://mediapipe.dev/)  
- [OpenCV](https://opencv.org/)  
- [PyAutoGUI](https://pyautogui.readthedocs.io/en/latest/)  
- [Tkinter](https://docs.python.org/3/library/tkinter.html)  

