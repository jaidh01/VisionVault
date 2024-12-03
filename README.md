# VisionVault  

VisionVault is an innovative project that transforms the way we capture and document moments. By integrating an ESP32-CAM mounted on goggles, this system allows users to stream a live video feed and capture images effortlessly with a keystroke. The captured images are processed through the Gemmini Vision API to generate detailed descriptions, creating a virtual memory bank.  

## Features  
- **Live Video Feed**: Stream visuals from an ESP32-CAM in real-time.  
- **Instant Image Capture**: Press "c" to save an image from the feed.  
- **Image Description**: Generate meaningful descriptions via the Gemmini Vision API.  
- **Hands-Free Operation**: Capture moments without using a phone or camera.  

## Applications  
Personal memory archival, remote surveillance, and assistive technology for visually impaired individuals.  

## How It Works  
Mount the ESP32-CAM on goggles or a suitable frame and connect it to a network. The Python script streams the live feed, allowing users to press "c" to capture an image. This image is sent to the Gemmini Vision API, which returns a detailed description.  

## Prerequisites  
- Arduino IDE
- ESP32-CAM module  
- Python 3.7+  
- Libraries: `opencv-python`, `requests`, `flask`  
- Access to the Gemmini Vision API  

## Installation  
Clone the repository: 
```bash
git clone https://github.com/your-username/VisionVault.git
```
and navigate to the folder.
Install dependencies with 
```bash 
pip install -r requirements.txt
```
Add your Gemmini API key in the `.env` file: `GENAI_API_KEY = "your-gemmini-api-key"`.  

## Usage  
Run the script with `python file_name.py`. View the live feed and press "c" to capture an image and get its description.  

## Future Enhancements  
Planned features include speech-to-text for hands-free control, support for additional APIs, and a mobile app interface.  

## Contributing  
Contributions are welcome! Fork the repository and submit a pull request.  

## Acknowledgments  
Special thanks to the Gemmini Vision API, OpenCV, and the Python community for their support.  
