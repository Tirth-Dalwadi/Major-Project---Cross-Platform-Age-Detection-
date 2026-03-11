# Major-Project
Cross-Platform Approach to Self-Reported Exact Age Detection in Social Media

**Author: Tirth Bhupendra Dalwadi**

This project implements a high-precision Natural Language Processing (NLP) pipeline designed to extract the exact age of users based on their self-reported statements across different social media platforms. By leveraging BERT-based architectures, the system accounts for the stylistic variations between microblogging (Twitter/X) and long-form discussion (Reddit).

**Project Thesis:**  https://drive.google.com/file/d/1z0McxU2Euqg7mqdla-p4I_Ld3Q8H3y5T/view?usp=sharing

## 🚀 **Overview**
Traditional age detection often categorizes users into broad brackets (e.g., 18–25). This project shifts the focus toward exact age extraction, which is critical for digital safety, personalized recommendation engines, and demographic research.

**Models used:** BERT (Bidirectional Encoder Representations from Transformers)

**Data Sources:** Semeval Dataset comprising of Twitter Tweets and Reddit Posts

**Core Challenge:** Distinguishing between literal age reports ("I am 22") and figurative/contextual mentions ("When I was 10...").

## 🛠️ Technical Stack
**Language:** Python

**Frameworks:** PyTorch / Hugging Face Transformers

**Data Processing:** Pandas, NumPy, Regex (for initial heuristic filtering)

**Environment:** Optimized for high-performance backend execution


## 📊 Key Features
**Cross-Platform Normalization:** Handles the "shorthand" nature of Twitter alongside the conversational depth of Reddit.

**Contextual Awareness:** Uses Transformer-based attention mechanisms to verify if a mentioned number actually refers to the user's current age.

**High CGPA-Standard Documentation:** Designed with academic rigor, following the methodology used in my undergraduate thesis at Jamia Millia Islamia.
