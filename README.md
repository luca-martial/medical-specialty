[![GitHub Issues][issues-shield]][issues-url]
[![Forks][forks-shield]][forks-url]
[![GitHub Stars][stars-shield]][stars-url]
[![Contributors][contributors-shield]][contributors-url]

# Medical Specialty Prediction with Spark NLP

The goal of this project was to predict medical specialties (surgery, internal medicine, medical records, other) based on a corpus of 4999 medical transcriptions using Spark NLP. The dataset was scraped by Tara Boyle, scraped from a Transcribed Medical Transcription Sample Reports and Examples website and published on Kaggle. The version used in this project was compiled by Carlos Salgado for Natural Language Processing using the scraped medical transcription corpus and custom-generated clinical stop words and vocabulary.

**Note: the notebook can be opened and run in Google Colab.**

The following models were tested:

- DL Classification with Universal Sentence Encoder
- DL Classification with BERT Sentence Embeddings
- DL Classification with BioBERT (Clnical) Sentence Embeddings
- DL Classification with BioBERT (MedNLI) Sentence Embeddings
- Logistic Regression with Universal Sentence Encoder
- Logistic Regression with CountVectorizer
- Logistic Regression with TF-IDF
- Random Forest with Universal Sentence Encoder
- Random Forest with CountVectorizer
- Random Forest with TF-IDF

## Contributing

Any contributions you make are really helpful!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingContribution`)
3. Commit your Changes (`git commit -m 'Add some AmazingContribution'`)
4. Push to the Branch (`git push origin feature/AmazingContribution`)
5. Open a Pull Request

## Reporting Issues

Does something seem off? Make sure to [report it](https://github.com/luca-martial/medical-specialty/issues).

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[issues-shield]: https://img.shields.io/github/issues/luca-martial/medical-specialty.svg
[issues-url]: https://github.com/luca-martial/medical-specialty/issues

[forks-shield]: https://img.shields.io/github/forks/luca-martial/medical-specialty.svg
[forks-url]: https://github.com/luca-martial/medical-specialty/forks

[stars-shield]: https://img.shields.io/github/stars/luca-martial/medical-specialty.svg
[stars-url]: https://github.com/luca-martial/medical-specialty/stargazers

[contributors-shield]: https://img.shields.io/github/contributors/luca-martial/medical-specialty.svg
[contributors-url]: https://github.com/luca-martial/medical-specialty/contributors
