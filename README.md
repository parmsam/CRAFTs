# CRAFTs

A collection of [SolveIt](https://solve.it.com/) notebook utilities for working with YouTube, arXiv papers, and notebook enhancements.

## Notebooks

| Notebook | Description |
|---|---|
| [arxivhtml2md.ipynb](arxivhtml2md.ipynb) | Converts arXiv papers to Markdown by fetching HTML-rendered versions from ar5iv.org or arxiv.org/html, parsing them with BeautifulSoup, and exposing section-by-section access with a tool-friendly API. |
| [embedyt.ipynb](embedyt.ipynb) | Embeds a YouTube video inline in a notebook using `pytube` and `IPython.display.YouTubeVideo`. |
| [playlistyt.ipynb](playlistyt.ipynb) | Retrieves all video URLs from a YouTube playlist and fetches metadata (title, views, length, etc.) for a list of videos using `pytubefix`. |
| [transcriptyt.ipynb](transcriptyt.ipynb) | Fetches the captions/transcript for a YouTube video using `youtube_transcript_api` and `pytube`. |
| [ttsbuton.ipynb](ttsbuton.ipynb) | Injects text-to-speech playback buttons into notebook prose cells using the browser's Web Speech API, with word-by-word highlighting and voice enumeration. |
| [yt2viz.ipynb](yt2viz.ipynb) | Captures frames from YouTube videos using `ffmpeg` and `pytubefix`, including single-frame, multi-frame, and an AI tool wrapper returning base64-encoded JPEG frames. |
