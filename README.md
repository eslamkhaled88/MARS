# MARS
Automation System for writing content writers  


# Overview
This project comprises a sophisticated Python script dedicated to the management and processing of educational content. The system is designed to automate the extraction, organization, transcription, and dissemination of educational data. With a focus on optimizing educational content workflows, this script integrates various technologies and methodologies to handle a diverse array of data formats and sources.

# Features
* 1 - Environment Setup and Data Retrieval: Initializes the environment, updates system packages, installs essential Python libraries, and mounts Google Drive for cloud-based file access.
* 2 - CSV File Editing and Folder Creation: Manipulates "courses.csv" to extract course names from MP3 URLs, organizes data into folders for streamlined automation.
* 3 - Downloading and Organizing MP3 Files: Downloads MP3 files, organizing them by course names into specific Google Drive folders.
* 4 - Transcription with Whisper ASR: Utilizes OpenAI's Whisper Automatic Speech Recognition model for transcribing audio content, incorporating a hyperparameter optimization grid search to enhance accuracy.
* 5- Text Extraction from Word Documents: Extracts and cleans text from Word documents containing Egyptian Arabic, structuring it for further processing.
* 6 - 6Data Transformation and Mapping: Processes and maps skills and objectives data from Excel files to course content, saving the mappings in JSON format.
* 7- Final Matching and Formatting: Merges data from scripts, transcriptions, and questions into a unified format, outputting the consolidated data to new JSON files.
* 8 - Data Cleaning and Structuring: Organizes files into subfolders based on their usage and type, facilitating efficient data management.
* 9 - System Post Requests: Supports sending JSON data to external APIs through defined POST request functions, enabling integration with external systems.
# Setup
* Clone the repository to your local machine.
* Ensure Python 3.x is installed.
* Install the required libraries using
```bash

pip install -r requirements.txt
````

* Configure Google Drive access by following the provided setup instructions in the config directory.
Usage

To start the process, run 
```bash
python main.py
````
# Follow the on-screen prompts to select the desired operations.
### Dependencies
* Python 3.11x
* Google Drive API
* OpenAI Whisper
* Additional Python libraries as listed in requirements.txt


### Acknowledgments
OpenAI for the Whisper ASR model.
The Python community for invaluable libraries and support.
