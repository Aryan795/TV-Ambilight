Real-Time TV Ambilight with Raspberry Pi and WS2812B LEDs

📖 Overview

This project creates an immersive ambient lighting system that dynamically matches the colors displayed on your TV in real-time. It captures video output, processes the frames to extract dominant colors, and drives an LED matrix to extend the on-screen colors to your room's lighting.

🛠️ Hardware Components

Raspberry Pi 4 (or newer) as the processing unit
HDMI to USB capture card (e.g., Elgato Cam Link 4K)
WS2812B addressable LED strips (144 LEDs/m recommended)
5V 10A power supply with proper fusing
Level shifter (74AHCT125) for 3.3V to 5V signal conversion
Capacitors (1000µF) for power stabilization
💻 Software Stack

Python 3.8+ for video processing and LED control
OpenCV for frame capture and color analysis
HyperLed for efficient LED control
Flask for web interface
