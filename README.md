# YouTube-Video-Summariser
Youtube Transcript Summarizer is a Chrome Extension that allows users to get a summarized version of the transcripts of YouTube videos with a single click. It utilizes Natural Language Processing (NLP) algorithms such as Latent Semantic Analysis (LSA) and state-of-the-art Huggingface Transformer models to efficiently summarize the transcripts of YouTube videos with a single click. It is built on a Flask Backend REST API to expose the summarization service to the client.

## Requirements
- The following python modules must be installed to run the API
  - ```flask```
  - ```youtube-transcript-api```
  - ```transformers```

## Instructions
- Run ```app.py``` to start the summarizer API.
- Load the custom extension into any Chromium browser.
- Go to any YouTube video and click on the extension logo to start summarizing.

## Features  
- Summarizes YouTube video transcripts employing advanced NLP techniques.
- Utilizes Latent Semantic Analysis (LSA) for extractive summarization of very long transcripts.
- Leverages Transformer models for abstractive summarization of shorter transcripts.
- Allows the user to adjust the maximum length of the summarized text through dynamic truncation.
- Adopts a language-agnostic approach and supports transcript summarization even for videos without subtitles.
- Employs an asynchronous XMLHttpRequest to ensure non-blocking communication with the Flask Backend.
