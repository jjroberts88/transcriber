# transcriber
Conversion of audio files to text using Whisper from OpenAI with a simple GUI

This is my first project in Python.
It uses Whisper, the brilliant, opensource, automatic speech recognition model from OpenAI.
The GUI is very basic/functional at present.
My inspiration for this was for the potential use in clinical settings as the data and transcription can be processed locally.

Audio files can be 'drag and dropped' or manually added for selection.

The 'transcribe' button sends the selected audio file to the model. The result is returned as text to the textbox and is automatically added to the clipboard for use in a word processor/email.

The model can be changed between any of the available options.
The smaller models run faster but accuracy is reduced.

|  Size  | Parameters | English-only model | Multilingual model | Required VRAM | Relative speed |
|:------:|:----------:|:------------------:|:------------------:|:-------------:|:--------------:|
|  tiny  |    39 M    |     `tiny.en`      |       `tiny`       |     ~1 GB     |      ~32x      |
|  base  |    74 M    |     `base.en`      |       `base`       |     ~1 GB     |      ~16x      |
| small  |   244 M    |     `small.en`     |      `small`       |     ~2 GB     |      ~6x       |
| medium |   769 M    |    `medium.en`     |      `medium`      |     ~5 GB     |      ~2x       |
| large  |   1550 M   |        N/A         |      `large`       |    ~10 GB     |       1x       |

I will continue to make improvements/changes.
I'm grateful for any feedback and advice

