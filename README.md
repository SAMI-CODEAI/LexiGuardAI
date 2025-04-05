📄 **LexiGuardAI v2.0 — AI-Powered Contract Risk Analyzer**  
Streamlit · Google Gemini 1.5 Flash · PyMuPDF · docx · Seaborn  

Submitted for: Google Solution Challenge 2025  
UN SDG Focus: Decent Work and Economic Growth (SDG 8), Reduced Inequalities (SDG 10)  

---

🌟 **Overview**  
LexiGuardAI is a GenAI-powered legal compliance tool that helps OTT platforms (like Aha) automatically analyze licensing agreements. By using advanced clause detection and risk evaluation models, LexiGuardAI simplifies contract reviews and flags risky terms in seconds.

---

🎯 **Problem Statement**  
Content licensing agreements are often dense and filled with legal jargon, making them difficult to understand and risky to sign without legal expertise. OTT startups especially face:

- Time-consuming manual contract reviews  
- Hidden legal risks and ambiguities  
- Lack of affordable legal guidance  

LexiGuardAI solves this by providing:  

- Instant clause-level analysis using AI  
- Risk-level tagging with detailed reasoning  
- Visual dashboards and downloadable audit trails  

---

🧠 **Key Features**  

| Feature                      | Description                                                                 |
|-----------------------------|-----------------------------------------------------------------------------|
| 📄 Contract Upload          | Upload `.pdf`, `.docx`, or `.txt` files for instant analysis               |
| 📚 Clause Categorization     | Identifies key legal sections (e.g., IP Rights, Termination, Indemnity)     |
| ⚠️ Risk Evaluation           | Flags Low / Medium / High risk clauses with AI-backed justifications        |
| 📊 Visual Insights           | Includes heatmaps, bar charts, and category-wise risk breakdowns           |
| 📁 Clause Audit Trail        | Download detailed reports as CSV or JSON                                    |

---

🚀 **Tech Stack**  

- **Frontend**: Streamlit  
- **LLM API**: Google Gemini 1.5 Flash  
- **Document Parsing**: PyMuPDF, python-docx  
- **Visualization**: Seaborn, Matplotlib  
- **Language**: Python 3.11+

---

🛠️ **Installation & Usage**

Clone the repository:  
```bash
git clone https://github.com/your-username/sami-codeai-lexiguardai.git
cd sami-codeai-lexiguardai
```

Install dependencies:  
```bash
pip install -r requirements.txt
```

Set your Gemini API key (in environment variables or inside the script):  
```python
GEMINI_API_KEY = "your_gemini_api_key"
```

Run the app:  
```bash
streamlit run LexiGuardAi.py
```

---

📈 **How to Use**  
- Upload a contract document  
- Click **"Analyze Contract"**  
- View visual summaries and clause breakdowns  
- Download the clause audit for record-keeping  
- Review detailed risk reasons for each clause  

---

🌍 **Impact Alignment: UN SDGs**  

✅ **SDG 8** — Empowers startups and creators with legal clarity, promoting fair digital employment  
✅ **SDG 10** — Reduces inequality in legal access through free and intelligent contract review  

---

📚 **Future Enhancements**

- 🔐 Firebase authentication for personal dashboards  
- 🇮🇳 Support for Indian legal documents (NSE/BSE contracts)  
- 🗣️ Local language support for wider adoption  
- 🤖 AI chat assistant for clause explanations  
- 🧾 Multi-document comparison and portfolio management  

---

🤝 **Contributing**  
Pull requests are welcome!  

```bash
# Fork the repository
# Create a new branch
git checkout -b your-feature-name

# Make your changes
# Commit and push
git push origin your-feature-name

# Open a Pull Request
```

---

📄 **License**  
Licensed under the [MIT License](LICENSE).  

---

📬 **Contact**

For queries, feedback, or collaborations:  
📧 your.email@example.com  
🔗 GitHub: [github.com/your-username](https://github.com/your-username)

Made with ❤️ for the Google Solution Challenge 2025  

