# Swahili_Classification_Project
# SWAHILI AUDIO PREDICTION: AN AUTOMATIC SPEECH RECOGNITION (ASR) PREDICTIVE MODELING PROJECT
## Introduction
![image](Readme_image.jpeg)
Swahili, originating on the East African coast, acted as a significant lingua franca, influenced by interactions between Bantu communities and Arab traders. Thriving city-states like Kilwa and Zanzibar boosted its prominence. In Automatic Speech Recognition (ASR) projects, Swahili's unique phonetics and dialects are a compelling challenge. ASR aims to transcribe spoken Swahili into text, making it useful for transcription and translation. Successful ASR for Swahili requires tailored models that adapt to the language's nuances. This technology plays a vital role in preserving and promoting Swahili's linguistic and cultural heritage, fostering cross-cultural communication and expanding the language's utility.

## Problem Statement
Swahili, also known as Kiswahili, has a rich history that spans centuries and is now one of the most widely spoken languages in Africa, with millions of speakers across various countries. Today, Swahili is not only a language of communication but also a symbol of cultural heritage and identity for millions of people in East Africa and beyond. Its history reflects the dynamic nature of language, shaped by trade, migration, colonization, and cultural exchange over the centuries.
With the increasing availability of digital audio content in Swahili, AnalytiX Insights aims to develop automated systems that can classify and categorize Swahili audio recordings for various applications, including speech recognition, content recommendation, and language learning tools.

## Main Objective
To develop an automated system for converting basic Swahili audio into written text using speech recognition technology.

## Specific Objectives
1. To develop a machine learning model capable of translating Swahili audio recordings.
2. To deploy a model that transcribes the recorded audio files.
3. To provide recommendations for further enhancements and applications.


## Experimental Designing

* Data Collection
* Data Preprocessing
* Exploration Data Analysis
* Feature Extraction
* Modelling
* Evaluation
* Deployment
* Conclusion
* Recommendations

## Metric of Success
Accuracy:
* The ratio of correctly recognized words to the total number of words in the reference transcription. A high accuracy rate will indicate a successful ASR system, as it signifies the system's capability to understand and convert spoken language into text with a high level of correctness.

Word Error Rate[WER]
* It quantifies the accuracy of the system by comparing the transcribed text to the reference text and measuring the number of insertions, deletions, and substitutions required to align them. A lower WER will indicate a higher level of success, as it represents a closer match between the system's output and the expected transcript.


Data Understanding
The data used in this project was collected by 300 contributors based in Kenya. It consists of recordings of twelve different phrases spoken in Swahili.Here are the 12 words and their English translations. You need to predict the Swahili word; the English is here for interest's sake.
| SWAHILI  | ENGLISH  |
| -------- |:--------:|
| Ndio     | Yes      |
| Hapana   | No       |
| Mbili    | Two      |
| Tatu     | Three      |
| Nne     | Four      |
| Tano     | Five      |
| Sita     | Six      |
| Saba     | Seven      |
| Nane     | Eight      |
| Tisa     | Nine      |
| Kumi     | Ten      |
| Moja     | One      |



## Conclusions
The CNN model is the best-performing model with an accuracy of 95% and a 5% word error rate.
We deployed the model and it can transcribe the Swahili audio files.


## Recommendations
To expand the scope of this project by incorporating a broader range of Swahili audio recordings, including longer sentences and passages.
To ensure that the model can handle a wide range of audio file formats as our project mainly dealt with .wav     format.
Use a powerful GPU device to train the model on big audio files. Make sure the audio quality is good to improve accuracy and speed, as poor audio can lead to errors and delays.




