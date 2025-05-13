# File Organizer

A multithreaded file and folder organizer written in Python.  
The program sorts files into predefined categories based on file extensions, normalizes file names, unpacks archives, and removes empty folders.

This project is a great demonstration of:
- Python multithreading
- File system manipulation
- Clean code practices
- Practical utility script for everyday use

## 🚀 Features

- Sorts files into categories:
    - Images (`.jpeg`, `.png`, `.jpg`, `.svg`)
    - Videos (`.avi`, `.mp4`, `.mov`, `.mkv`)
    - Documents (`.doc`, `.docx`, `.txt`, `.pdf`, `.xlsx`, `.pptx`)
    - Music (`.mp3`, `.ogg`, `.wav`, `.amr`)
    - Archives (`.zip`, `.gz`, `.tar`)
    - Others (uncategorized files)

- Unpacks archives into dedicated subfolders
- Normalizes file names (removes special characters and converts to safe format)
- Removes empty folders recursively
- Runs with multithreading for better performance

## 💻 Requirements

- Python 3.8+
- Libraries:
    - `shutil`
    - `os`
    - `pathlib`
    - `threading`
    - `sys`

*(All are standard Python libraries — no additional installation needed.)*

## 📝 Usage

1. Clone this repository:

```bash
git clone https://github.com/pawel455/file_organizer.git
cd file_organizer
