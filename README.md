# Subtitle Generator

Subtitle Generator is a simple and easy-to-use Python application that can generate subtitle images from text, remove silence from MP4 files, and even provide text-to-speech (TTS) capabilities with an external API.

It is meant for creators that want basic subtitles as images, without having to deal with one-by-one convertion or paid/limited services. 

## Disclaimer

This app is meant to serve a smaller target of users who want to generate just subtitles images in the order of 10 to 50 images. I have not tested higher amounts or too many different styles. A big change in configurations could result in unwanted appearance. 

Use at your own risk, especially after the implementation of text to speech features. 

## Features

1. **Subtitle Generation**: Paste your text in the provided text field, select the "Subtitles" mode, and click "Run". The application will generate PNG images for each line of text and save them in a timestamped folder.
2. **Silence Removal**: Select the "Remove Silence" mode, select the MP4 file and click "Run". The application will output a series of MP3 files, each containing a non-silent segment from the original audio.
3. **Text-to-Speech**: Coming soon! This feature will utilize the Azure voice Microsoft Text-to-Speech API to convert your text into speech, you can customize the code related to text-to-speech to use an open source or free option.

![home screen](readme-images/image1.png)

## How to Use

1. Open the application.
2. For Subtitle Generation, paste your text in the text field at the top (a new subtitle is detected when there is an empty line)
3. For Silence Removal, use the "Select MP4 file" button to choose your file.
4. Select your desired mode from the drop-down menu.
5. Click "Run" to execute the chosen operation.

You can customize the look of the subtitle directly into the code itself.

## Future Enhancements

- Integration with Azure voice Microsoft Text-to-Speech API for Text-to-Speech feature.
- Enhanced user interface with settings/customizations tab.
