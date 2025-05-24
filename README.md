# OpenCv_ESP_IOT
Create an IoT system using Wemoss (ESP8266) to recognize objects and take actions based on the results.
🛠️ Workflow:
1️⃣ Image Capture & Recognition:
Used my laptop or smartphone camera to capture images.
Implemented YOLOv5 (a pre-trained object detection model) for image recognition on my laptop.
Saved results in a JSON format.
2️⃣ Flask Server Hosting:
Set up a local Flask server to host the JSON file containing recognition results.
Made it accessible to the ESP8266 via HTTP.
3️⃣ ESP8266 Integration:
Configured the ESP8266 to fetch JSON data from the Flask server.
Parsed the JSON to identify detected objects and triggered IoT actions (e.g., turning on an LED if a specific object like a "cat" was detected).
🌐 Key Features:
Scalable Architecture: Easily extendable to other IoT devices or cloud-based APIs.
Efficient Communication: ESP8266 dynamically fetches and acts on the recognition results.
Real-Time Processing: Leveraged the power of YOLOv5 for accurate and fast object detection.
📦 Tools & Technologies Used:
ESP8266/Wemoss
Python (Flask, OpenCV, PyTorch)
YOLOv5 for Object Detection
ArduinoJson for ESP8266 Parsing
📈 Outcome:
A fully functional IoT-based object recognition system that bridges AI and IoT seamlessly! 
Built using free or open-source tools, making it highly cost-effective and accessible.
