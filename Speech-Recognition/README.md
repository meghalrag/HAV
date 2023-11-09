# SPEECH RECOGNITION APP


Python-Speech-Recognition
---------------------------

This repository on performing Speech Recognition that convert speech or audio to Python using Google Speech Recognition Engine.


The original article
-------------------------

To see full article with explanation on source code from this repository **[Click here](https://kalebujordan.com/python-speech-recognition)**


Getting started 🔧
--------------------
Firstly before we begin exploring the source code, you might wanna *clone* or *download* the repository
just as shown below;

### Installing

First, clone this project from github using git command or git gui application like [fork](https://github.com/meghalrag/HAV/fork).
```
git clone https://github.com/meghalrag/HAV.git
```

Making environment for project to isolation python installing libraries for this project only.
```
conda create -n env python=3.10.9
conda activate env
```

Installing all libraries needed by this project using [pip](https://pypi.org/project/pip/).
```
cd Hav/Speech-Recognition
pip install -r requirements.txt
```

Recognition From Microphone 
----------------------------


The first Example *app.py* consist of python code to perform speech recognition 
on sound that is directly fed from Microphone 

To run the Example do the following

```bash 
python app.py 
```
```
Out:
Adjusting noise 
Recording for 4 seconds
Done recording
Recognizing the text
Decoded Text : Python is awesome
```

Recognition From Audio File 
-----------------------------

The second Example *app_audio.py* consist of a python code to perform speech recognition from 
sound loaded from local audio file 

To run the Example do the following 

```bash
python app_audio.py 
```
```
Out:
Done recording
Recognizing the text
Decoded Text : python programming is the best of all by Jordan
```

Recognizing From Long Audio File 
-----------------------------------

Incase you have a long audio File, loading plus processing it, It takes a quite a while therefore 
the best way is to break the long audio source from file into small chunks and then performing 
speech Recognition on those chunks 

The script *long_audio.py* consist of Python demo code just to that 

To run the example do the Following 

```bash 
python3 app_audio.py 
```

```
Out:
Done recording
Recognizing the text
Decoded Text : python programming is the best of all by Jordan
```

## Authors

**Meghalrag** - *Initial work* - [meghalrag](https://github.com/meghalrag)