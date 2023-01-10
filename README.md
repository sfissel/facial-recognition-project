# FACIAL RECOGNITION GROUP PROJECT

## Intro/Problem:
Facial recognition technology relies on massive datasets to “learn” faces to accurately identify or verify the identity of a person. It captures, analyzes, and compares patterns based on a person’s facial features. Facial biometrics continues to be the preferred biometric benchmark above all other methods because it’s easy to deploy and implement, does not require any physical interaction with the end-user, and is very quick.

Facial recognition is now being implemented across many industries because of its wide applicability, benefits, and convenience. Many issues, small and large, that we once faced a decade ago are being solved thanks to this technology.

For example, it can be used to:
- Help find missing people and identify perpetrators
- Protect businesses against theft
- Improve medical treatment, mainly for genetic disorders
- Strengthen security measures in banks and airports as preventative measure
- Unlock sensitive information on mobile devices
- Make shopping more efficient
- Drastically reduce human touchpoints, especially during the pandemic
- Help organize photos

## Background:
Facial recognition technology analyzes the unique features of a person’s face to verify their identity. Generally, FRT creates a template of the target’s facial image and compares the template to pictures of preexisting data of a face.

There are different types of FRT:
- **Traditional:** Uses a photo of a face to analyze the basic geometry of the features
- **3-Dimensional:** Uses 3D sensors and cameras at various angles. The sensors capture the shape and contours of the face
- **Surface texture analysis:** Captures a patch of skin and then analyzes characteristics of the face such as lines and pores
- **Thermal:** Uses a similar algorithm as traditional FRT, but it helps recognize a face when the face is hard to recognize in visible light and it can recognize facial blood vessel structure

## Question: 
### **Can we create a machine learning model that accurately identifies and detects the correct person from a group of people with similarities in their appearances (male, middle aged, caucasian, short, brown hair, some facial hair, etc.)?**
- Might be easier for a machine learning model to identify the correct person when people have more distinguishable facial features

## Three Actors:
- **Hugh Jackman:** Australian actor, 54 years old (Wolverine)
- **Ryan Reynolds:** Canadian-American actor, 46 years old (Deadpool)
- **Jake Gyllenhaal:** American actor, 42 years old (Mysterio in “Spider-Man”)

## Why them?
Due to the limitations of our computing resources, we are limiting the project to three different possible male celebrities. These three actors are internationally famous, so we can easily access a lot of their images which will allow us to train our machine-learning model with hundreds of pictures of them, including different angles and facial expressions. They have some common characteristics in their appearances which will make it interesting for our model to learn and be able to distinguish between them.
