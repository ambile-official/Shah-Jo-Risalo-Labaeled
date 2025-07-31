# Shah Abdul Latif Bhittai’s Poetry Dataset – “Shah Jo Risalo”

## Developed by:
**Abdul Majid Bhurgri Institute of Language Engineering (AMBILE), Hyderabad**  
Under the administrative control of the **Culture, Tourism, Antiquities & Archives Department, Government of Sindh**.

## Dataset Overview:
The **"Shah Jo Risalo" Dataset** is a rich linguistic and literary resource comprising **43,779 Sindhi poetic verses** extracted from the 30 traditional **Surs** of Shah Abdul Latif Bhittai’s magnum opus. Each verse is paired with a **Sindhi-language explanation**, primarily derived from the authoritative interpretations of **Dr. Nabi Bakhsh Baloch**.

This dataset offers profound insights into the **philosophical**, **spiritual**, and **cultural** themes embedded in the poetry, making it an invaluable asset for Sindhi literature researchers, linguists, educators, and AI/NLP developers.

## Dataset Features:
- **Total Verses**: 43,779 poetic lines from 30 classical Surs
- **Language**: Clean Sindhi script in Unicode format
- **File Format**: CSV file titled `Shah Jo Risalo labeled.csv`

## CSV Structure:
- **melody (سر)**: Name of the Sur
- **chapter (داستان)**: Subsection within the Sur
- **chapter_verse_number**: Verse number within the dastan
- **poetry_text (بيت)**: Original Sindhi poetic verse
- **explanation (وضاحت)**: Sindhi interpretation of the verse
- **keywords**: Search-optimized terms
- **compiler_name**:Name of the compiler of various versions of Shah Jo Risalo.**

## Applications:
- Natural Language Processing (NLP) research in Sindhi
- AI-based Sindhi chatbots and conversational agents
- Development of educational tools for literature learning
- Text-to-Speech (TTS) system training
- Verse classification and sentiment analysis tasks
- Digital preservation and promotion of Sindhi literary heritage


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
Special thanks to the AMBILE team for their efforts in **data curation**, **cleaning**, and **formatting**, and to all the scholars and compilers who contributed to preserving the legacy of Shah Abdul Latif Bhittai.

## Contact:
For any queries, collaboration opportunities, or contributions, please contact:
- **Email**: [technicalteam@ambile.pk](mailto:technicalteam@ambile.pk)
