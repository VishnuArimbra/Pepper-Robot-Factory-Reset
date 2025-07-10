# Pepper Robot Factory Reset using Flasher

This repository contains a steps for performing a **factory reset** the **Pepper robot**. The tool allows to restore Pepper to its original factory settings, which can be useful for troubleshooting, maintenance, or preparing the robot for a new user.

## Prerequisites

Before using the flasher tool, make sure to have the following:

1. **NAO Flasher Tool**:  
   Download the NAO Flasher compatible with the operating system.
   [Download NAO Flasher Tool](https://aldebaran.com/en/support/kb/nao6/downloads/nao6-software-downloads/)

2. **NAOqi Operating System Image**:  
   Appropriate NAOqi image for the robot model should be downloaded.
   [Download the NAOqi 2.5.10](https://www.robotlab.com/support/factory-reset-on-pepper-robot)

3. **Unformatted USB Drive**:  
   Use a Unformatted USB Drive USB drive. If needed, follow this video guide on how to unformat a USB drive, starting at the minute at 2:33.
   [Directions to unformat a USB drive](https://www.youtube.com/watch?time_continue=171&v=GOroldPAEzE) 

4. **Fully Charged Pepper Robot**:  
   Ensure the Pepper robot is fully charged before starting the reset process.

## Creating the USB Flasher

1. **Run the NAO Flasher Tool**:  
   - Navigate to the folder containing the NAO Flasher tool.
   - Right-click on the batch file and select "Run as administrator".

2. **Select the NAOqi Image**:  
   - Click **Browse** and choose the NAOqi image downloaded earlier.

3. **Choose the USB Drive**:  
   - Select the unformatted USB drive from the list in the flasher tool.

4. **Enable Factory Reset Option**:  
   - Check the box for **Factory Reset**.

5. **Start the Flashing Process**:  
   - Double-check all the selections and click **Write**.  
   - The tool will notify when the flashing process is complete, and can safely remove the USB drive.

> **Note**: If, do not want to perform a factory reset, leave the **Factory Reset** box unchecked.      
> **Note**: The textbox may say **"NAO V4 Image detected"**. This is a bug in the program and not a cause for concern.
---

## Performing the Factory Reset on Pepper

1. **Power Off Pepper**:  
   Ensure the Pepper robot is turned off before proceeding.

2. **Insert the USB Flasher**:  
   Insert the USB drive into Pepper's head.

3. **Initiate the Reset**:  
   - Press and hold the **chest button** on Pepper for at least 6 seconds until the LED starts flashing rapidly in **blue**.
   - The reset process will take between 10 to 30 minutes. During this time, the lights on Pepper's head and ears will change patterns.

4. **Completion**:  
   - Once the reset is finished,It will produce a startup sound.
   - Pepper will announce:  
     "I successfully updated my system. I am now running version x.y.z. I successfully completed my factory reset. All of my data and settings have been reset."
