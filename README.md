<h1>Smart Hat for Visually Challenged Person</h1>

<p>This project aims to develop a smart assistive hat designed to aid visually challenged individuals in navigating their surroundings with more independence. The system utilizes a Raspberry Pi, a camera, and an earphone to detect obstacles and provide real-time audio feedback to the user.</p>

## Key components
- Raspberry Pi: Serves as the core processing unit, handling the data from the camera and managing obstacle detection algorithms.
- Camera: Captures live video of the user's surroundings and helps in detecting objects and potential obstacles.
- Earphone: Provides audio alerts and guidance based on the processed data from the Raspberry Pi, offering real-time information to the user.

## Objectives
- To Develop a system to alert the user about nearby obstacles. Implement a face recognition system to identify individuals and inform the visually challenged user.
- To Design smart hat equipped with Raspberry pi and connectivity to detect obstacles, recognize objects, and provide real-time feedback to the user.
- To Conduct extensive testing and user feedback sessions to iterate and refine the design, ensuring that the final product meets the needs and preferences of visually challenged users. 


## Features
- Camera for Object Recognition.
- Speech Recognition and Voice Commands.
- Environment Awareness.
- Low Power Consumption.
- Compact and Wearable Design.
- Customizable Features.

## Design:-
<p>
  <img src= "https://github.com/harshans5/Smart-Hat-for-Visually-Challenged-Person/blob/main/Setup%20and%20Outcome/reference%20design.png"/> 
</p>

## Components Used
- Respberry Pi
- Respberry Pi Camera Module
- Earphone
- SD card

## Software Requirement:
- [Raspbian OS](https://www.raspberrypi.com/software/)
> Raspbian OS is a free, Debian-based operating system optimized for the Raspberry Pi hardware. It provides a lightweight, flexible environment with pre-installed tools ideal for educational projects, programming, and hardware interfacing.

## Setup Instructions
1. **Hardware Setup:**
   - Raspberry Pi and Camera Module Connection - Attach the Raspberry Pi Camera Module to the camera interface on the Raspberry Pi using the ribbon cable. Ensure the cable is securely connected and the camera is properly seated.
   - Earphones Connection - Plug the earphones into the 3.5mm audio jack on the Raspberry Pi. If using USB earphones, connect them to a USB port.
     
2. ## Software Setup

To set up the software for your Raspberry Pi-based Smart Hat, follow these steps:

### 1. System Update and Library Installation

1. **Update the Raspberry Pi OS:**
   - Open a terminal on your Raspberry Pi and run the following commands to update the package list and upgrade installed packages:
     ```bash
     sudo apt-get update
     sudo apt-get upgrade
     ```

2. **Install Required Libraries:**
   - Install OpenCV, Python libraries, and text-to-speech (TTS) utilities by running:
     ```bash
     sudo apt-get install python3-opencv espeak
     sudo pip3 install SpeechRecognition gtts
     ```

### 2. Code Deployment

1. **Clone the Repository:**
   - Clone the project repository from GitHub and navigate into the project directory:
     ```bash
     git clone <repository_url>
     cd <repository_name>
     ```

2. **Run the Main Script:**
   - Execute the main Python script to start the system:
     ```bash
     python3 smart_hat.py
     ```
   - This script initializes the camera, performs object detection, and provides audio feedback through the earphones.

---

Make sure to replace `<repository_url>` and `<repository_name>` with your actual GitHub repository URL and name. This setup will get the necessary software components running on your Raspberry Pi to operate the Smart Hat.


## Usage
- Power on the device. The camera will capture obstacles in front of the user and provide audio feedback.
- You can visualize the obstacles on a monitor through the Raspbian OS.
## Result:
<p>The Raspberry Pi-based Smart Hat effectively detects and identifies everyday objects and people using advanced image processing. It provides clear audio feedback and real-time performance with greatly improving situational awareness and safety. This project can create impactful assistive technology. Future improvements should focus on enhancing sensor integration, algorithm efficiency, and incorporating haptic feedback.</p>
<p>

<p align="center">
  <img src="https://github.com/harshans5/Smart-Hat-for-Visually-Challenged-Person/blob/main/Setup%20and%20Outcome/Result-1.png" width="45%" />
  <img src="https://github.com/harshans5/Smart-Hat-for-Visually-Challenged-Person/blob/main/Setup%20and%20Outcome/Result-2.png" width="45%" />
</p>


## Under the Guidence:
- [Prof.Ashwini A M](https://www.youtube.com/@AshwiniAM-012)

## Authors:
- [HARSHAN S](https://www.linkedin.com/in/harshan-s/)
- [K SANTOSH](https://www.linkedin.com/in/k-santosh-102a73310/)
- [MANOJ KUMAR C S](https://www.linkedin.com/in/manoj-kumar-c-s-a981a0254/)
- [NAVEEN N P](https://www.youtube.com/@naveen451)
