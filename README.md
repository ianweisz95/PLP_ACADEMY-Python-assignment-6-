# Ubuntu Image Fetcher

## Project Description
This project is inspired by the Ubuntu philosophy: "I am because we are." It is a mindful tool for connecting to the global web community, fetching shared images respectfully, and organizing them for later appreciation.

The Python script prompts the user to input an image URL, downloads the image, and saves it into a local directory called `Fetched_Images`. It handles errors gracefully to respect the connectivity challenges and community sharing nature of the internet.

## Features
- Prompts user for an image URL
- Creates `Fetched_Images` directory if missing
- Downloads and saves the image locally with appropriate filename
- Uses `requests` library with error handling for reliable downloads
- Respects Ubuntu principles of community, respect, sharing, and practicality

## Usage
1. Ensure Python 3 is installed.
2. Install the `requests` library if not already installed:
