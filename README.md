![image](https://github.com/cabelo/nurse_please/assets/675645/0c545667-7fa6-49ec-b64d-4f012a65c9ee)

# nurse_please
It is a system based on OpenVINO, to reproduce sound alert and send help message to patients in hospital or bedridden.

## Intel Technologies
OpenVINO, Movidius NCS

## Overview / Usage
### Problem addressed by the project

Many patients need constant monitoring, such as bedridden, elderly, and people with degenerative and non-degenerative diseases. In many situations it is not possible to provide a 24x7 caregiver. To help those patients using technology, the Nuple Project was created (Nuple is an Acronym for “Nurse, Please”).

The basic idea behind the project is to fire an alarm (that could be a siren, a lamp, an app notification or even an emergency call) through the detection small movements on the arms of the patient on a bedridden situation. This alarm will sign the caregiver, nurse or relative responsible by the patient that his attention is needed.

## Key Benefits

This technology allows behavioral monitoring through body movement, combined with cognitive state monitoring in real time, allowing it to be used not only to daily basis monitoring but also to use this data to do proactive clinical analysis of the monitored individuals. The generated alarms can also be integrated with different communication platforms, including social media. The data can also be stored, allowing the usage of AI techniques to prevent future episodes based on historical data.

This predictive capability is extremely important for certain conditions, because alarms and alerts can be generated to anticipate a situation and avoid a most critical episode for the patient.

Being an open source solution, Nuple can be used, customized and extended to provide technology support for healthcare professionals, and companies can use this product to implement or integrate with their existing solutions.

## Methodology / Approach
### Idea and implementation methodology

Nuple (Nurse, Please) it’s a computer system that “sees everything”. The project uses Computer Vision techniques based on OpenCV, OpenVINO optimized for Intel platforms. It explores Deep Learning based AI techniques such as Convolution Neural Networks, aligned with pose detection algorithms.

Aligning those two technologies, it is possible to detect the skeleton vertices, compute the internal angles and using mathematic and behavioral concepts such as triangle similarities, the system is able to detect in real time a set of pre-programed actions that can be used to fire the alert.

An additional feature under development is the use of Cognitive Biometry to identify the patient state. For that, the FOCI device will be used to read states as stress, calm, tired, focused and others, allowing the solution to also send alarms based on the patient’s cognitive state.

The project will be free, and its evolutions and future features would be possible with the donation of individuals and companies. All source code is licensed under an opensource license, allowing collaborations not only to the source code but also with the solution’s localization and other contributions.

Nuple will be installable on any Intel based computer (6 gen or above), as well as single board computers using Movidius Compute Sticks. This will allow that anyone with a computer and a webcam will be able to use the system to monitor the patient the need to at home, hospital or any other environment.

## Technologies Used
- OpenVINO
- OpenCV 3.4.1 or above)
- Movidius NCS
- FOCI IoT device
- Intel based computer (6 gen or above)
