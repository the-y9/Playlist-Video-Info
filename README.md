# Playlist Information Extractor

This Python script extracts video titles and durations from a YouTube playlist. The extracted data is saved to both a `.txt` and a `.csv` file.

## Table of Contents

- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Error Handling](#error-handling)

## Requirements

The script requires the following Python packages:
- `pytube`: for fetching playlist data from YouTube.
- `tqdm`: for showing progress bars.

### Installation

If these packages are not installed, you can install them using:

```bash
pip show pytube || pip install pytube
pip install tqdm
```

## Usage

To use the script, you need to run the Python code provided below. The script fetches the title and duration of each video from the YouTube playlist and saves the information into `.txt` and `.csv` files.

## Error Handling

In case the script encounters an error while fetching video information (such as title or duration), it logs `"error"` for the title and `"na"` for the duration of the problematic video in the output files.
