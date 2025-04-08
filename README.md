**Speech Phoneme Analysis and Classification Project**

This project builds a simple speech classifier for vowel-based phonemes and analyzes the results.  

Data:  subset of the Accents of the British Isles (ABI-1) Corpus with 14 different regional accents and 10 male and 10 female speakers for each accent, reading this list:
Heed, hid, head, had, hard, Hudd, hod, heard, hoard, hood, who’d, hade, hid, hoid, hoed, howd, heered, hared, hured, heed 

The CSV file contains:
• Speaker label 
• Gender (M/F) 
• Word 
• Vowel Phoneme (in ARPABET notation) 
• A class number e.g. 1, 2, 3 (each particular ARPABET symbol should have the same class number/label) 
• Formant 1 
• Formant 2 
• Formant 3 

OcenAudio was used to extract formant frequencies and a K-Nearest Neighbor classifier was used to classify speech phonemes based on formant frequencies.  
Both Euclidean and Manhattan distance metrics were used in addition to F1 score for classification evaluation.
