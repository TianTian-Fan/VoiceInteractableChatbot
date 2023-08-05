# Ontario Tech University-Capstone-InteractableVoiceChatBot

## ***Team Information***
- **Tiantian Fan** - Programmer <sub>/ Avatar Modeler</sub> - tiantian.fan@ontariotechu.net
- **Hossain Alinqi** - UI Designer <sub>/ Post Effect Designer / Prop Modeler</sub> - hossain.alinaqi@ontariotechu.net
- **Gary Liu** - Animation - gary.liu@ontariotechu.net

## ***Project Information***
### ***Python Side***
For running the Python file, make sure to install the following libraries:
```
-pip install openai
=======================
-pip install whisper
=======================
-pip install SpeechRecognition
=======================
-pip install flask
```

- [OpenAI](https://github.com/openai/openai-python)
- [Whisper](https://github.com/openai/whisper)
need ffmpeg ```choco install ffmpeg``` using [Chocolatey](https://chocolatey.org/install)
and [PyTorch](https://pytorch.org/get-started/locally/)
- [SpeechRecognition](https://github.com/Uberi/speech_recognition)
need PyAudio ```pip install pyaudio```
- [Flask](https://flask.palletsprojects.com/en/2.3.x/installation/)

**Important: Put your own [OpenAI API](https://openai.com/blog/openai-api) key in line 8 of the code**

### ***Unity Side***
Can't directly upload the project into GitHub due to the maximum file limit, so I provide a link to download the project:

[Project Download](https://drive.google.com/file/d/1uYsbyf87-v0hFqGun_58hJD2LB9w36VB/view?usp=drive_link)

**Important: Put your own [AWS](https://aws.amazon.com/console/) keys(accessKey and secretKey) in line 99 of the script named WebRequest**

## ***Known Issues***
- **Can't provide the executable of Python file and Unity project because the packaged executable does not contain the API key.**
- **Ask the first question ASAP(maximum 12 seconds) after you see the avatar, otherwise, the avatar will not talk anymore.**
- **The Avatar will repeat the answer after you do not ask a new question for 30 seconds.**

## ***Demo Video***
[![Demo](https://github.com/TianTian-Fan/VoiceInteractableChatbot/assets/71342545/0e761e38-3236-4140-bede-dec4112c3a94)](https://youtu.be/Jk9x4ebHmUk)
