### **QBHit**

---
Query by Humming (QBH) is a music information retrieval system that allows users to search for songs by humming or singing a melody. The system matches the hummed input to a database of songs and returns the most likely match. 

---
#### **System Architecture**

1. **Audio Input**: The user hums or sings a melody, which is recorded as an audio file.
2. **Feature Extraction**: Extract features like MFCC, Chroma, Spectral Contrast, and Tempo from the audio.
3. **Database**: A collection of songs with pre-extracted features.
4. **Matching Algorithm**: Compare the hummed input features with the database using Dynamic Time Warping (DTW) or other similarity measures.
5. **Output**: Display the best-matching song.


