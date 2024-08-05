# WhatsApp Chat Analyzer

This project analyzes WhatsApp chat data using Streamlit. It provides various visualizations and statistics to help understand chat patterns.

## Features

- Total messages, words, media shared, and links shared
- Monthly and daily timelines
- Activity maps (weekly and monthly)
- Wordcloud of the most common words
- Emoji analysis

## How to Run
## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/whatsapp-chat-analyzer.git
    cd whatsapp-chat-analyzer
    ```

2. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

3. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```

4. Open the application in your browser at `http://localhost:8501`.

## Usage
1. Upload your WhatsApp chat text file.
2. Select the user you want to analyze.
3. Click on "Show Analysis" to view the statistics and visualizations.

## Author
Vivek Pal
## Files

- `app.py`: The main application file
- `helper.py`: Contains helper functions for analysis
- `preprocessor.py`: Contains preprocessing functions
- `requirements.txt`: List of dependencies
- `stop_hinglish.txt`: Stop words file

## Sample

Upload your WhatsApp chat export file in the `.txt` format to analyze.

## License

This project is licensed under the MIT License.
