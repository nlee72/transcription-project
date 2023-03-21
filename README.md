# Audio Transcription and Summarization
This project aims to transcribe audio using the Google Chrome web browser and OpenAI's GPT-3 model.
The audio is recorded and saved as a WAV file.
The transcription is then fed to the GPT-3 model to produce a summary of the audio content.
## Usage
1. Run the code in the Jupyter notebook.
2. The notebook will prompt you to record audio. Press the button to start recording and then press it again to stop.
3. The audio will be saved to a file called recording.wav.
4. The audio file will be transcribed using the OpenAI Whisper model.
5. The key points of the transcription will be summarized using the OpenAI GPT-3 model.
6. The summary will be printed out to the console.
## Install necessary libraries
To run this project, you will need to install the following libraries:

ffmpeg-python
openai
## Credits
Some of the code used in this project is not original.
* The code for recording audio and converting it to a WAV file is based on this notebook https://colab.research.google.com/gist/ricardodeazambuja/03ac98c31e87caf284f7b06286ebf7fd/microphone-to-numpy-array-from-your-browser-in-colab.ipynb#scrollTo=H4rxNhsEpr-c
* The code for using Whisper to transcribe the audio is based on the Whisper documentation.
