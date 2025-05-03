# 📊 WhatsApp Chat Analyzer

A Streamlit web application that provides deep analytics on your WhatsApp group or personal chat data. Simply export your chat from WhatsApp, upload the `.txt` file, and visualize everything from word clouds and emoji stats to timelines and heatmaps.

🔗 **Live Demo**: [Click here to use the app](https://whatsappchatanalysis-9lue.onrender.com/)

---

## 📂 Folder Structure

whatsapp-chat-analyzer/
│
├── app.py # Main Streamlit app
├── helper.py # Helper functions for analysis & visualization
├── preprocessor.py # Preprocessing of raw WhatsApp exported chat
├── stop_hinglish.txt # Custom stop words for Hinglish (Hindi-English mix)
├── requirements.txt # Python dependencies
└── README.md # Project documentation



---

## ⚙️ Features

- 📈 **Statistics**: Total messages, words, media shared, and links
- 🕐 **Timelines**: Monthly and daily message trends
- 📅 **Activity Maps**: Most active days, months, and hours
- 🔥 **Busiest Users**: Top contributors in group chats
- ☁️ **Word Cloud**: Visualize the most common words
- 📊 **Common Words**: Horizontal bar chart of top-used words
- 😂 **Emoji Analysis**: Emoji usage frequency and charts
- 🧭 **Heatmap**: Weekly activity heatmap by day and hour

---

## 🛠️ Installation (Local)

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer

# 2. Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run the Streamlit app
streamlit run app.py
```
## 📤 How to Export WhatsApp Chat
1. Open WhatsApp chat (group or personal)
2. Tap on 3 dots > More > Export Chat
3. Choose Without Media
4. Transfer the .txt file to your computer
5. Upload it into the app

## 🧪 Dependencies
Main libraries used in this project:

- streamlit
- pandas
- matplotlib
- seaborn
- wordcloud
- emoji
- urlextract

All are listed in requirements.txt.

## 🚀 Deployment on Render
App is deployed on Render. To deploy your own:

1. Push code to GitHub
2. Create a new Web Service on Render
3. Use:
   - Build Command: pip install -r requirements.txt
   - Start Command: streamlit run app.py --server.port=10000 --server.enableCORS=false
4. Add stop_hinglish.txt to root directory if not already
5. Done! Your app will go live with a public URL

## 🙋‍♂️ Author
Vivek Pal
- 📧 paljivivek12@gmail.com
- 🔗 GitHub • LinkedIn

## 📝 License
This project is licensed under the MIT License.

## ⭐ Feedback / Support
If you like this project, give it a ⭐ on GitHub.
For feature requests or bugs, open an Issue.



---

Let me know if you'd also like:

- A `requirements.txt` (if not created yet)
- `.gitignore` for large or unnecessary files
- Folder with proper screenshots (dashboard, word cloud, etc.)
- `LICENSE` file

Would you like me to generate any of these right now?
