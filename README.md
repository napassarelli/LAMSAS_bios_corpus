# LAMSAS_bios_corpus

## Introduction
For my master's thesis, "'Local, But Intelligent': Language Ideologies in the Informant Biographies of the Linguistic Atlas Project," I conducted a qualitative discourse analysis of 583 informant biographies collected as part of the Linguistic Atlas Project (LAP). Focusing primarily on analysis of pragmatic features within the informant biographies, this project reveals the ways that language ideologies, indexicality, and enregisterment are encoded into the LAP more broadly. This repository contains both the data set I used for this project as well as the processing procedures for how I transcribed and digitized this data for corpus analysis. 

## Data
The data for this study specifically comes from the Linguistic Atlas of the Middle and South Atlantic States (LAMSAS), a sub-project of the LAP that represents 1,162 informants from more than 10 states. For this project, I digitized and collected a total of 583 unique informant biographies from the original LAMSAS collection. There are two datasets used in my thesis. First, "LAMSAS_informant_biographies" is a collection of the full informant biography texts, including demographic information and a subjective 'character sketch' written by the LAP fieldworker. Second, "LAMSAS_character_sketches" excerpts just the subjective 'character sketch' without the additional demographic information. Each of these databases are available in two formats: first as a .db file (which I created using AntConc) and second as a compressed .zip folder containing the raw text files. 

## Data Processing
### Processing
My first step in preparing this data for analysis was to digitize and transcribe the original type-written paper informant biographies using a combination of image pre-processing and optical character recognition (OCR) programs: ImageMagick and Tesseract. "LAMSAS_processing_code" gives examples both the 'standard' and 'enhanced' image processing and OCR procedures to generate first-pass transcriptions of the original scanned documents.  
### Editing
After generating, these OCR-generated transcriptions required additional manual review and correction for processing errors. "LAMSAS_bio_corrections" documents the edits and corrections that reflect my personal judgments.
## Contact
If you have any questions, comments, or feedback about my data, methods, or work, please don't hesitate to contact me at npassarelli@uky.edu
