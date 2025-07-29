# Shah Abdul Latif Bhittai Poetry Dataset

## Overview:
The **Shah Abdul Latif Bhittai Poetry Dataset** contains a total of **43,779 Sindhi poetic verses** from the 30 traditional **Surs** of Shah Abdul Latif Bhittai’s *Shah Jo Risalo*. Each verse is paired with an explanation in Sindhi, primarily based on interpretations by Dr. Nabi Bakhsh Baloch. This dataset provides valuable insights into the philosophical, cultural, and spiritual significance of the poetry, making it an indispensable resource for Sindhi literature enthusiasts, linguists, and researchers.

## Dataset Structure:
The dataset is available in a CSV file named `Shah Jo Risalo labeled.csv` and includes the following columns:

- **sur (سر)**: Name of the Sur (e.g., ڪلياڻ, سارنگ, حسيني).
- **text**: The specific poetic verse or line of poetry.
- **dastan (داستان)**: Subsection of the Sur (e.g., 1, 2).
- **dastan_verse_number**: The verse number within the specific Dastan.
- **poetry_text (بيت)**: The actual Sindhi verse or line of poetry.
- **explanation (وضاحت)**: The Sindhi-language explanation or interpretation of the verse, primarily by Dr. Nabi Bakhsh Baloch.
- **compiler_name**: Name(s) of the compiler(s). Notable contributors include:
  - Allama I. I. Qazi
  - Banhoo Khan Shaikh
  - Dr. Nabi Bux (28 Surs Explanation)
  - Dr. Ernest Trumpp
  - GM Shahwani
  - Gurbakh Shani
  - Mirza Qaleech Baig
  - Tara Chand Shokeeram
  - Usman Ali Ansari
  - Usman Diplai
  - Adwani Kaliyan
  - Dr. Nabi Bux Baloch (1165–1207 Hijri)
  - Dr. Nabi Bux Baloch (1269 Hijri and 1270 Hijri)
  - Dr. Nabi Bux Baloch (British Museum)

- **keywords**: Keywords relevant for search algorithms.

## Key Highlights:
- **Total Poetries**: 43,779 poetic verses.
- **Coverage**: Complete collection of the 30 traditional Surs of Shah Abdul Latif Bhittai’s *Shah Jo Risalo*.
- **Compilers**: Contributions from renowned compilers and scholars.
- **Language**: Clean Sindhi script in Unicode format.
- **Usage**: Includes simple Sindhi language explanations for each verse to aid understanding.
- **Ideal For**:
  - NLP research
  - Search engines for Sindhi poetry
  - Educational tools for learning Sindhi literature
  - AI-powered chatbots focused on Sindhi poetry

## Potential Uses:
- **AI Bots and Chatbots**: Develop AI bots and chatbots focused on Sindhi poetry.
- **Language Modeling**: Research on Sindhi literature and language modeling.
- **Educational Tools**: Create educational applications for learning Sindhi literature.
- **Text-to-Speech Systems**: Implement in systems focused on generating Sindhi poetry in speech.
- **Verse Classification**: Use for verse classification tasks in AI models.

## How to Use:
1. **Clone the repository or download the CSV file**.
2. Open the CSV file using Python or Excel:
   ```python
   import pandas as pd
   df = pd.read_csv("Shah_Jo_Risalo_labeled.csv")
   print(df.head())
## License:
This dataset is released under the **Creative Commons Attribution-NonCommercial 4.0 License**. It is intended for educational and research purposes only.

## Acknowledgments:
- The poetry of **Shah Abdul Latif Bhittai** serves as the inspiration for this dataset.
- Special thanks to the **AMBILE team** for their involvement in data compilation and cleaning.
- Thanks to all the **compilers** who contributed to the preservation and dissemination of Shah Abdul Latif Bhittai’s poetry.

## Contact:
For any queries, collaboration opportunities, or contributions, please contact:
- **Email**: [technicalteam@ambile.pk](mailto:technicalteam@ambile.pk)
