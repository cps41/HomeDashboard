# HomeDashboard
DIY project to display a dashboard on my home TV and use voice control to toggle functions.
# Foundation
The goal of this project is to create a dashboard with a joint calendar, a ToDo list, and a weather visual. It will also include a voice assistant that takes in voice commands to toggle the TV's power and inputs.
# Requirements
- Displays a calendar
- Displays upcoming events larger
- Displays a ToDo list
- Displays upcoming/overdo tasks larger
- Displays the weather
- Turns off automatically at night
- Turns on automatically in the morning
- Voice assistant turns TV on/off
- Voice assistant changes TV input
# Necessary Components
- Single Board Computer
    - Raspberry Pi (3+ ideal)
    - BeagleBone
    - ???
- USB Microphone
- HDMI Cable
# Software Integrations
- DAKboard API
    - For the actual dashboard
- cec-client
- Python
# ToDo
- Determine board reqs
- Find a usb mic
- Fix 3D printer to make a tidy case
# ALTERNATIVE IDEA
Use Google Actions to create the voice toggles and create an API on the SBC. This will then require a wireless connection and become an IoT project. It will also remove the need to obtain a USB mic and create a voice assistant. 
