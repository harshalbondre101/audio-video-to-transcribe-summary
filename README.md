# audio-video-to-transcribe-summary
# Audio/Video Transcription App

This Streamlit app is designed to transcribe audio content from uploaded video files and provide a summarized version of the transcribed text using OpenAI's GPT-3 model.

## Features

- **Transcription**: Extracts audio from uploaded video files (in .mp4 format) and transcribes the audio content.
- **Summarization**: Utilizes the GPT-3 model to generate a summary of the transcribed text.
- **Action Item Extraction**: Identifies and lists any tasks, assignments, or actions mentioned in the text.
- **Key Points Extraction**: Extracts and lists the main ideas, findings, or crucial topics discussed in the text.
- **Sentiment Analysis**: Analyzes the sentiment of the text and provides information on whether it's positive, negative, or neutral.

## Usage

### Prerequisites

- Ensure you have Python installed on your system.

### Installation

1. Clone this repository.
2. Install the required Python packages:

    ```bash
    pip install streamlit openai moviepy python-docx
    ```

### Running the App

1. Navigate to the directory containing the app files.
2. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```
3. The app interface will open in your default web browser.

### Usage Instructions

1. Upload a video file in .mp4 format using the "Upload a video file (mp4)" button.
2. Once the file is uploaded, the video player will display the uploaded video.
3. Click the "Extract Audio and Transcribe" button to initiate the transcription process.
4. The app will transcribe the audio content and display the transcription in the "Transcription" section.
5. A summarized version of the transcription will appear in the "Summary" section.
6. The app will generate a 'transcription_summary.docx' file containing both the transcription and summary.

## Note

- The app might take some time to process larger video files due to transcription and summarization tasks.

## Credits

- This app utilizes OpenAI's GPT-3 language model for transcription and summarization tasks.
