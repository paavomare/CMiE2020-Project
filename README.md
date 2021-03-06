# CMiE2020-Project
This repository contains a Python project on **analysing rhythmic patterns in *maracatu*** using **Music21** for the course **"Computational Methods in Ethnomusicology"** by Rafael Caro Repetto, Ph.D. at the Kunstuniversität Graz.

## Introduction
The Brazilian style of percussion music *maracatu de baque virado* is characterized by a prominent feature of its traditional rhythmic patterns, namely an accentuation of off-beat rather than on-beat notes as that is the case for other Brazilian percussion styles like *samba* or even most other genres around the world. During this experiment, transcriptions of the rhythmic patterns of the Austrian group **Maracatu Renascente** are analysed by using the Python toolkit **Music21** to find out what the concrete ratio between the elements of *maracatu* rhythm patterns, especially the ratio of accented on-beat and off-beat notes, actually is. 

## Content and Dataset
This repository contains the Jupyter notebook `Maracatu_Pattern_Analysis.ipynb`, which itself contains the program code and further explanations. The data can be found in the  directory `maracatu_patterns/` that contains the dataset, i. e. the MusicXML-files for the analysis, and the MuseScore- and the PDF-files of the patterns. 

## Use
The modules in `requirements.txt` need to be installed via `pip install -r requirements.txt`, otherwise the program will produce an error. Furthermore, if the repository is downloaded, the directory `maracatu_patterns` must remain in the same place as the Jupyter notebook, otherwise the path will be incorrect and the program will produce another error.
