# Music-Composition-AIML
Topic: Music Generation with LSTM and Music21

Description:
This project demonstrates the use of a Long Short-Term Memory (LSTM) neural network to generate musical sequences based on a dataset of MIDI files. The LSTM model is trained on a collection of MIDI files containing musical notes and chords. After training, the model is used to generate a new musical sequence, which is then translated into a MIDI file. The generated MIDI file is further processed using the Music21 library to create a visual representation of the musical notation. The project includes code for data preprocessing, model training, music generation, MIDI file creation, and musical notation visualization.

Key Features:

LSTM neural network for music generation.
MIDI file generation from the LSTM model.
Visual representation of musical notation using Music21.
Code for data loading, preprocessing, and model training.
Generated music sequence can be customized in terms of length and style.
Instructions:

Data Preparation:

MIDI files with musical content are used for training the LSTM model.
The glob module is employed to load MIDI files from a specified directory.
LSTM Model Training:

The LSTM model is constructed using the Keras library.
The model is trained on the extracted musical notes and chords.
Music Generation:

The trained model is used to generate a new music sequence.
MIDI File Creation:

The generated music sequence is converted into a MIDI file.
Musical Notation Visualization:

The Music21 library is utilized to load and visualize the generated MIDI file as musical notation.
The MuseScore software is integrated into the Colab environment for notation rendering.
Dependencies:

Keras (for LSTM model)
Music21 (for MIDI file and musical notation handling)
Note:
Ensure that MuseScore is properly set up in the Colab environment for the correct rendering of musical notation.






