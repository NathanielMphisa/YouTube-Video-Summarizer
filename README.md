# YouTube Video Summarizer

This project provides a tool to summarize YouTube video transcripts. It extracts the transcript from a YouTube video and uses natural language processing techniques to generate a concise summary.

## Task

The project automates the process of summarizing YouTube videos, saving time for users who need a quick overview of the video content.

## Workflow

1.  **Input:** YouTube URL
2.  **Extraction:** The script extracts the Video ID from the URL.
3.  **Transcript Fetching:** The YouTube Transcript API is used to fetch the video's transcript.
4.  **Summarization:** The transcript is summarized using NLP techniques.
5.  **Output:** A concise summary of the video.

## Libraries Used

* Regex (`re`)
* YouTube Transcript API (`youtube_transcript_api`)
* Sumy (`sumy`)
* NLTK (`nltk`)
* OpenAI (`openai`)

## Key Features

* Transcript extraction from YouTube videos
* Text summarization

## Getting Started

1.  Clone the repository.
2.  Ensure you have the required libraries installed (`pip install pytube youtube-transcript-api sumy nltk openai`).  You might also need to download NLTK resources (e.g., `nltk.download('punkt')`).
3.  Run the Jupyter Notebook `YouTube Summarizer.ipynb`.
4.  Provide the YouTube video URL when prompted to generate the summary.

## Proposed Features

* Multi-language Support
* Browser Extension
* Summarization Modes (e.g., bullet points, paragraph)
* Visual Summaries
* Bookmarking and Saving Summaries
* Voice Summary Generation
