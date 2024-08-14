# Bengaluru Linux / IoT Workshop   

## Developing Applications on the Qualcomm RB3 Gen 2  

This comprehensive workshop empowers developers to build innovative multimedia and AI applications, powered by RB3 Gen2 Development Kit using Qualcomm Linux. The exercise's overall goal is to capture feedback to enhance the development experience and build out the RB3 Gen2 library of sample applications.   

## Scope 
### Overview 

- Do not sacrifice sleep, food, or health to complete this trial. Your well-being is more important than everything else.   

- If you have not done so, [set up your Qualcomm ID](https://myaccount.qualcomm.com/signup), confirm your email, then [sign the PKLA](https://qualcomm.com/agreements) using your Qualcomm ID.  This gives you access to the documentation. 

- Choose a workflow below (Audio, Visual or AI) and tell Rain - the facilitator - letting them know which path you’re going to explore. If you are concerned you will not have time to finish or get stuck and are tempted to switch workflows, please do not switch without speaking with Rain first.  

- Set up your Host System using the requirements listed [here](https://docs.qualcomm.com/bundle/resource/topics/80-70014-254/github_workflow_unregistered_users.html?product=1601111740013072) (scroll down to ‘Host machine requirements'). You will set up either a virtual host on your existing OS or an Ubuntu 22.04 host on baremetal. You will also need an external monitor and an HDMI cable for the sample applications.  

When you run into issues, search through the [CE Forums](https://mysupport.qualcomm.com/supportforums/s/) so that engineering may address them directly. It is vitally important that when you run into an issue, you search FIRST as the issue and workaround may already be posted by someone else. For real-time chat, discussions, and asynchronous communication, please visit the [Qualcomm Developers Discord Server](https://discord.gg/qualcommdevelopernetwork). This platform facilitates interaction among the community. 

Maintain a Feedback Form as you follow your workflow. Write down any time you are lost, confused, or frustrated and, if applicable, how you resolved it.   

## Introduction and Setup ~1 hr  

### Introduction  

- [Overview of the RB3 Gen2 Development Kit and its components](https://docs.qualcomm.com/bundle/resource/topics/80-70014-115/dev-kits.html?product=1601111740013072)  

- [What is open source?](https://opensource.com/resources/what-open-source) What does it mean to [share my work online](https://en.wikipedia.org/wiki/Open-source_software)?  

### What is in the Box  

- [Detailed explanation of the components in the Vision kit](https://docs.qualcomm.com/bundle/resource/topics/80-70014-253/getting_started.html?product=1601111740013072)  

### Setup and Configuration  

- [Set up your host machine](https://docs.qualcomm.com/bundle/resource/topics/80-70014-253/set_up_the_device.html?product=1601111740013072)

#### Windows on Snapdragon using WSL

- Enable "Turn Windows features on or off" : select Windows Subsystem for Linux  
- Restart the machine  
- Using Windows PowerShell, run the command "wsl --update"  
- Once completed, run the command "wsl --install Ubuntu-22.04"
- Breathe (it'll take a few minutes to install)  
- Reboot the system   
- Run the command "wsl --set-default-version 2" and then **repeat** the installation command (wsl --install Ubuntu-22.04" (we have no explanation why you have to do it twice)  
- Enter your UNIX (don't be scared) username (unix) and password (unix)  

- Connect the RB3 Gen2 device to the host  

## Focused Development ~4-6 hrs  

Please work on one of three application development workflow based on your specialization: Audio, Visual, or AI application development. Please follow the documentation and work on creating one sample application that you may want to publish online under an open-source license.  

### Workflow One: Audio Application Development   

#### Introduction to Audio Capabilities  

- [Overview of audio processing features on the RB3 Gen2](https://docs.qualcomm.com/bundle/resource/topics/80-70014-16/overview.html?product=1601111740013072&facet=Audio)  

- [Exploration of the audio sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70014-50/multimedia-sample-applications.html)  

#### Hands on Development  

- [Set up the development environment for audio applications](https://docs.qualcomm.com/bundle/resource/topics/80-70014-16/verify.html?product=1601111740013072&facet=Audio)  

- Develop a simple audio recording and playback application  

- Implement audio effects and filters  

#### Testing and Feedback  

- Test the application on the RB3 Gen2  

### Workflow Two: Visual Application Development  

#### Introduction to Visual Capabilities  

- [Overview of visual processing features on the RB3 Gen2](https://docs.qualcomm.com/bundle/resource/topics/80-70014-20/overview.html?product=1601111740013072&facet=Video)  

- [Exploration of the video sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70014-50/multimedia-sample-applications.html)  

#### Hands on Development  

- Develop a simple camera application for image capture and processing  

- Implement basic image filters and effects  

#### Testing and Feedback  

- Test the application on the RB3 Gen2  

### Workflow Three: AI Application Development  

#### Introduction to AI Capabilities  

- [Overview of AI processing features on the RB3 Gen2](https://docs.qualcomm.com/bundle/resource/topics/80-70014-15/overview.html?product=1601111740013072&facet=Artificial%20Intelligence)  

- [Exploration of the AI sample applications](https://docs.qualcomm.com/bundle/publicresource/topics/80-70014-50/ai-ml-sample-applications.html)  

#### Hands on Development  

- [Set up the development environment for AI applications or models](https://docs.qualcomm.com/bundle/resource/topics/80-70014-15B/offering.html?product=1601111740013072)  

- Develop a simple AI application using pre-trained models via https://aihub.qualcomm.com/

- Implement basic AI functions such as object detection or speech recognition  

#### Testing and Feedback  

- Test the application on the RB3 Gen2  
