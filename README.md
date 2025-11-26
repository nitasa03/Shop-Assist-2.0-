# ShopAssist 2.0 🛒🤖

ShopAssist AI is a backend chatbot designed to make online shopping easier by providing **personalized laptop recommendations**.  
It combines **large language models** with **rule-based functions** to ensure accurate, reliable, and tailored results.

----------------------------------
## 🚀 Features
- Conversational interface to understand user intent
- Function calling for:
  - Fetching laptop data from a dataset
  - Filtering recommendations based on specs
- Tailored laptop recommendations (RAM, CPU, price, etc.)
- Backend‑only design (no UI layer)

------------------------------------
## 🛠 Tech Stack
- **Python 3.9+**
- **OpenAI GPT-4** (function calling)
- **pandas + numpy** for dataset parsing and filtering
------------------------------------
## 📂 Project Structure
- ShopAssist_2.0/
- ──**shopassist.py**    # Core chatbot logic
- │── **dataset.csv**    # Laptop dataset
- │── **requirements.txt**  # Dependencies
- │── **README.md**         # Project documentation
- │── **.gitignore**        # Ignore unnecessary files

----------------------------------
## ⚙️ Setup Instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/nitasa03/ShopAssist-2.0.git
   cd ShopAssist-2.0

2. - Install dependencies:
     pip install -r requirements.txt
   - Export your OpenAI API key:
     export OPENAI_API_KEY="your_api_key_here"

3. - Run the chatbot backend:
     python shopassist.py
----------------------------------
## 🧑‍💻 Example Usage

User: Recommend laptops under $1000 with 16GB RAM

Bot: Here are 3 laptops that match your criteria...

----------------------------------
## 📌 Future Improvements
- Add UI (Streamlit/Gradio) for interactive demo
- Expand dataset to other product categories
- Integrate cloud deployment (GCP/AWS/Azure)
----------------------------------
## 📧 Contact
Created by Nibedita
For collaboration or feedback, reach out via GitHub Issues or email.


