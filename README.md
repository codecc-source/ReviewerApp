########################### Personal project for SO to help her study :) ###########################  

###### Note that all the files save (JSON, MP3, DOCX) are all saved in the same folder this program is saved to. Ex: if the program was saved on Downloads/Reviewer then the other files will be saved there as well. ######                                                                                  

The Notes Reviewer tool is designed to help users create and review notes for various subjects. It allows users to input questions and answers, including text-based questions and visual questions (images). Users can then review these notes in a quiz-like format to test their knowledge. Additionally, the tool provides functionalities to export notes to a Word document, save notes to JSON format for future reference, and even save notes as MP3 files for audio playback. The saved JSON notes can also be uploaded to another project, the quizlet app website (https://codecc-source.github.io/quizletAppTest/), this can be accessed via mobile and user/s can do a quizlet on the go.

## Features
1. **Input Questions and Answers**:
   - Users can input questions and corresponding answers using text input fields.
   - For visual questions, users can browse and select images to use as questions.

2. **Review Notes**:
   - Users can review their notes in a quiz-like format.
   - The tool randomly presents questions from the notes, and users input their answers.
   - After completing the review, users receive feedback on their performance.

3. **Export Notes**:
   - Notes can be exported to a Word document for printing or further editing.
   - Each note is formatted with its question and answer.

4. **Save/Load Notes**:
   - Users can save their notes to a JSON file for future reference.
   - Notes can be loaded from a JSON file to continue working with previously saved notes.

5. **Undo Last Note**:
   - Allows users to undo the addition of the last note.

6. **Edit Notes**:
   - Users can edit existing notes, modifying both the question and the answer.

7. **Show Notes List**:
   - Displays a list of all notes entered by the user.

8. **Save Notes as MP3**:
   - Converts notes to audio files in MP3 format for listening on the go. Note that it may take a while depending on the length of the notes created and may seem like your machine is freezing, but its not and you just have to wait for it to finish.

9. **Instructions**:
   - Provides detailed instructions on how to use each feature of the tool.

## How to Use
1. **Input Questions and Answers**:
   - Enter a question in the "Enter Question" field.
   - Enter the corresponding answer in the "Enter Answer" field.
   - Optionally, browse and select an image for visual questions.

2. **Add Note**:
   - Click the "Add Note" button to add the question-answer pair to the notes list.

3. **Review Notes**:
   - Click the "Review Notes" button to start reviewing the notes.
   - Answer the presented questions and receive feedback on your performance.

4. **Export Notes**:
   - Click the "Export to Word" button to export notes to a Word document.
   - Enter a file name and find the DOCX file in the folder of the program.

5. **Save/Load Notes**:
   - Enter a note title (e.g., "Subject_A_Prelim_Notes.json").
   - Click "Save Notes to JSON" to save notes in JSON format.
   - Use "Load Notes from JSON" to load previously saved notes.

6. **Additional Functionality**:
   - Use "Clear Notes" to start over with an empty notes list.
   - "Undo" allows you to remove the last entered note.
   - "Edit Note" lets you modify existing notes.
   - "Show Notes List" displays all entered notes for reference.
   - "Save Notes as MP3" converts notes to audio files for listening.

## Dependencies
- Tkinter: GUI toolkit for Python.
- Pillow (PIL): Python Imaging Library for image processing.
- python-docx: Library for creating and modifying Word documents.
- gTTS: Google Text-to-Speech API for converting text to speech.
- json: Library for parsing JSON data.

## Usage
To use the Notes Reviewer tool, execute the provided Python script. The GUI interface will open, allowing you to interact with the tool's features.

                                                           
