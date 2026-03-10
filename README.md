# # MP3_Tag_Radar

MP3_Tag_Radar is a command-line based application written in **C** that allows users to **view and edit metadata (ID3 tags)** of MP3 files.  
The project demonstrates concepts of **file handling, binary data processing, structures, and command-line arguments** in C programming.

MP3 files store additional information called **ID3 tags**, which include details such as **song title, artist name, album, year, genre, and comments**.  
This project reads those tags from the MP3 file and allows users to update them easily through the terminal.

---

## 🚀 Features

- 📖 Read MP3 metadata (ID3v2 tags)
- ✏️ Edit MP3 tag information
- 🖥️ Command-line interface
- ⚡ Fast processing using file handling
- 🛠️ Error handling for invalid inputs
- 📂 Supports multiple tag fields

---

## 🛠️ Technologies Used

- **C Programming Language**
- **File Handling (Binary Files)**
- **Structures and Pointers**
- **Command Line Arguments**
- **Data Manipulation**

---

## 📂 Project Structure

MP3_Tag_Radar/

│

├── main.c # Main program entry point

├── read_tags.c # Functions to read MP3 tags

├── edit_tags.c # Functions to modify MP3 tags

├── tag_struct.h # Structure definitions

├── utils.c # Helper functions

└── README.md # Project documentation



▶️ Usage


1️⃣ View MP3 Tag Information

./mp3_tag_radar -v song.mp3


This will display metadata such as:

Title

Artist

Album

Year

Content 

Comment


2️⃣ Edit MP3 Tag Information

./mp3_tag_radar -e -t "New Title" song.mp3



🧾 Editing Options

| Option | Description  |
| ------ | ------------ |
| `-t`   | Edit Title   |
| `-a`   | Edit Artist  |
| `-A`   | Edit Album   |
| `-y`   | Edit Year    |
| `-g`   | Edit Genre   |
| `-c`   | Edit Comment |



Example:

./mp3_tag_radar -e -a "Arijit Singh" song.mp3




📚 Learning Objectives



This project helps in understanding:

Internal structure of MP3 ID3 tags

Binary file processing in C

Command-line tool development

Efficient data manipulation

Practical use of structures and pointers
