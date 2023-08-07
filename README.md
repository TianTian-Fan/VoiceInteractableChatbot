# Ontario Tech University-Capstone-InteractableVoiceChatBot

## ***Team Information***
- **Tiantian Fan** - Programmer <sub>/ Avatar Modeler</sub> - tiantian.fan@ontariotechu.net
- **Hossain Alinqi** - UI Designer <sub>/ Post Effect Designer / Prop Modeler</sub> - hossain.alinaqi@ontariotechu.net
- **Gary Liu** - Animation - gary.liu@ontariotechu.net

## ***Project Information***
This project is a voice interactable AI chatbot, it is based on OpenAI, Whisper, Flask, AWS Polly, and Oculus Lip Sync. We want to combine old fashion with new technology, so we made the style of environment like last century! It is so interesting to mix old and new together, and don't forget to ask any questions to the chatbot!

## ***Installation Guide***
### ***Python Side***
For running the Python file, make sure to install the following libraries(Python 3.10 recommended):
```
-pip install openai
=======================
-pip install openai-whisper
=======================
-pip install SpeechRecognition
=======================
-pip install flask
```

- [OpenAI](https://github.com/openai/openai-python)
- [Whisper](https://github.com/openai/whisper)
need ffmpeg ```choco install ffmpeg``` using [Chocolatey](https://chocolatey.org/install)**(It is recommended that installing chocolatey and ffmpeg in Windows PowerShell instead of cmd)**
and [PyTorch](https://pytorch.org/get-started/locally/)
- [SpeechRecognition](https://github.com/Uberi/speech_recognition)
need PyAudio ```pip install pyaudio```
- [Flask](https://flask.palletsprojects.com/en/2.3.x/installation/)

**Important: Put your own [OpenAI API](https://openai.com/blog/openai-api) key in line 8 of the code**

### ***Unity Side***(2021.3.11f recommended, not sure if there are issues with other version)
I am sorry that I can't directly upload the project into GitHub due to the maximum file limit(The avatar model and animation created by Character Creator and iClone are over 50MB), so I will provide a link to download the project instead:

[Project Download](https://drive.google.com/file/d/1uYsbyf87-v0hFqGun_58hJD2LB9w36VB/view?usp=drive_link)

If you encounter this when you try to open the Unity project:
![Issue](https://github.com/TianTian-Fan/VoiceInteractableChatbot/assets/71342545/4c1f6a32-8d51-43cf-a597-6ea22d7b9404)

Don't worry, you only need to following steps to solve this:
- Hit the "Continue" button to get into the project
- Download the package **[here]**(https://www.reallusion.com/auto-setup/unity/download.html), choose HDRP 12
- Extract the .zip file to a directory
- In Unity, open the **Package Manager** window and click the Add button, then select Add package from disk
- Navigate to where you placed the extracted files, select **package.json**
- The project should be good to go.

There are two scenes called "Hologram" and "PC". "Hologram" is clean and used for hologram effect, it only contains the avatar and necessary functions. In "PC", there are various prop models and post-effects to bring a better visual experience.

**Important: Put your own [AWS](https://aws.amazon.com/console/) keys(accessKey and secretKey) in line 99 of the script named WebRequest**

## ***Known Issues***
- **Because the API keys will automatically get abandoned if they become publicly viewable, so there will be no API keys in our source code. However, the executable of the Python file and Unity project need API keys to work properly, so we can't provide executables either. I am sorry if you think this installation guide is complex, but I believe it is the only way.**
- **In "PC" scene, Ask the first question ASAP(maximum 12 seconds) after you see the avatar, otherwise, the avatar will not talk anymore. The "hologram" scene doesn't have this issue.**
- **The Avatar will repeat the answer after you do not ask a new question for 30 seconds.**

## ***Demo and Screenshot***
Demo: https://youtu.be/Jk9x4ebHmUk

Screenshot:
![Screenshot](https://github.com/TianTian-Fan/VoiceInteractableChatbot/assets/71342545/e2567f6d-4eca-4c8f-a1db-c29061aea513)

For any issues and feedback:
tiantian.fan@ontariotechu.net

