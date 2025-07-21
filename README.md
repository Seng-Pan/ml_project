#  Food Assistance Chatbot

## Overview
An AI-powered chatbot that assists with:
- Recipe recommendations
- Nutritional analysis
- Allergy-aware meal planning
- Food image recognition

##  Usage Examples
1. Recipe Search:
   "Show me quick vegetarian pasta recipes"
2. Nutrition Query:
   Upload image + "How many calories in this dish?"
3. Allergy Filter:
  "High-protein breakfast without eggs"

## Features
| Feature | Description |
|---------|-------------|
| **Multimodal Input** | Process both text queries and food images |
| **Dietary Filtering** | Avoid allergens like nuts, gluten, etc. |
| **Nutrition Facts** | Calories, macros, and health metrics |
| **FAISS Search** | Instant recipe retrieval from 40K+ database |

## 🛠️ Setup

### Prerequisites
```bash
pip install streamlit transformers sentence-transformers faiss-cpu torch pillow
```

# Data Preparation

1. Download dataset: kaggle datasets download -d kmader/food41
2. Mount Google Drive (Colab) or update paths in app.py

# Launch
```bash
streamlit run app.py
```

License
MIT © Seng Pan
*Dataset: CC BY-NC-SA 4.0 (food41)*
