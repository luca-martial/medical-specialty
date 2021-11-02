[![GitHub Issues][issues-shield]][issues-url]
[![Forks][forks-shield]][forks-url]
[![GitHub Stars][stars-shield]][stars-url]
[![Contributors][contributors-shield]][contributors-url]

# Medical Specialty Prediction with Spark NLP

The goal of this project was to predict medical specialties (surgery, internal medicine, medical records, other) based on a corpus of 4999 medical transcriptions using Spark NLP. The corpus was scraped by [Tara Boyle](https://github.com/terrah27) from a [Transcribed Medical Transcription Sample Reports and Examples website](https://mtsamples.com/) and published on [Kaggle](https://www.kaggle.com/tboyle10/medicaltranscriptions). The version used in this project was compiled by [Carlos Salgado](https://github.com/socd06) for Natural Language Processing using the scraped corpus and custom-generated clinical stop words and vocabulary. This compiled version was published on [GitHub](https://github.com/socd06/medical-nlp) and is free to use.

**Note: the [notebook](https://github.com/luca-martial/medical-specialty/blob/main/medical_specialty_prediction.ipynb) can be opened and run in Google Colab.**

The following models were tested using Spark NLP's open source and licensed healthcare version:

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
