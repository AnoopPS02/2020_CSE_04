# 2020_CSE_04
## Alphanumeric Character Recognition in Audio/Text Based Captcha

By Anoop P S , Aafreen Hussain , Akshitha B S

### Captcha - Completely Automated Public Turing test to tell Computers and Humans Apart

CAPTCHAs are computer-generated tests that humans can pass but current computer systems cannot. CAPTCHAs provide a method for automatically distinguishing a human from a computer program, and therefore can protect Web services from abuse by so-called “bots.” Most CAPTCHAs consist of distorted images, usually text, for which a user must provide some description. Unfortunately, visual CAPTCHAs limit access to the millions of visually impaired people using the Web. Audio CAPTCHAs were created to solve this accessibility issue. Briefly, audio CAPTCHAs are sound files which consist of human sound under heavy noise where the speaker pronounces a bunch of digits consecutively. Generally, these sound files are composed of a set of words to be identified, layered on top of noise and some periodic and non-periodic noises to get difficult to recognize them with a program but not for a human listener. However, with the advancements in deep learning, it becomes easier to build deep learning models that can efficiently recognize text, image, and audio-based CAPTCHAs. So, we gather numerous randomly generated captcha files to train our neural network model and test the model’s ability to recognize characters from audio and image captcha files. The objective of this project is to identify alpha-numeric characters with the use of neural networks. We construct suitable neural network and train it suitably. Our model will be able to extract the characters one by one and map the target output for training purpose. Further, the performance of our model will be evaluated based on various performance metrics like accuracy, sensitivity, specificity, precision, recall.

### BLOCK DIAGRAM
![Block diagram!](https://github.com/AnoopPS02/2020_CSE_04/blob/main/Block%20Diagram.png)
### Softwares Installed
      1. Python3 - Packages required:

             Captcha, TTS, ffmpeg, librosa, pillow. 

      2. IDE - Visual Studio Code
