# TP1_Interface_Mfcc_Mgg
A graphical user interface made with PyQt creator to treat a audio and apply different functions on It 

This Python code demonstrates audio processing techniques using the PySide6, librosa, numpy, and scikit-learn libraries. It provides a graphical user interface (GUI) with three buttons to load a WAV audio file, extract Mel-frequency cepstral coefficients (MFCC) from the audio file, and fit a Gaussian mixture model (GMM) to the MFCC features to create a new audio file.

The GUI consists of two figures that display the original and processed audio, and a layout with three buttons. The "Load WAV Audio" button opens a file dialog to choose a WAV file, loads the audio file using librosa, and displays the original audio waveform in the "Original Audio" figure. The "MFCC Function" button calculates the MFCC features using librosa and displays the result as a spectrogram in the "Processed Audio" figure. The "GMM Function" button fits a GMM to the MFCC features using scikit-learn, creates a new audio file using the GMM features, and saves it to a file selected in a file dialog.
