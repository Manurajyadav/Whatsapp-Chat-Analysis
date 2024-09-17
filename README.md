# WhatsApp Chat Analyzer 📊

Welcome to the **WhatsApp Chat Analyzer**! This project uses **Streamlit** to provide insights and visualizations of WhatsApp chat data. Analyze message counts, media shared, activity patterns, and more.

## Features 🌟

- **Upload WhatsApp Chat Files**: Upload your `.txt` chat export file.
- **Message Statistics**: Get total message counts, word counts, media shared, and links shared.
- **User-based Analysis**: Analyze data for a specific user or the entire group.
- **Timelines**:
  - 📅 Monthly timeline of messages.
  - 📆 Daily timeline of messages.
- **Activity Map**:
  - 📆 Most active day of the week.
  - 🗓️ Most active month.
  - 🌡️ Weekly activity heatmap.
- **Busiest Users**: Identify the most active users in a group chat.
- **Word Cloud**: Generate a word cloud of the most common words used.
- **Common Words**: Display frequently used words (excluding stop words).
- **Emoji Analysis**: Breakdown of the most frequently used emojis.

## Installation 🚀

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repository/whatsapp-chat-analyzer.git
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage 💻

1. **Run the Streamlit app:**
   ```bash
   streamlit run app.py

2. **Upload your WhatsApp chat `.txt` file** using the file uploader in the sidebar.

3. **Select the user** or "Overall" to analyze data for the entire chat.

4. **Click on "Show Analysis"** to view the results, including statistics, visualizations, and emoji usage.

## File Structure 📂

- `app.py`: Main application file for the Streamlit dashboard.
- `helper.py`: Functions for data processing and generating statistics, timelines, and visualizations.
- `preprocessor.py`: Handles preprocessing of the WhatsApp chat data.
- `stop_hinglish.txt`: List of stop words excluded from analysis.
- `requirements.txt`: Lists project dependencies.

## Preprocessing 🛠️

- The chat data is parsed to extract messages, user names, and timestamps.
- **Columns generated include:**
  - `user`: Sender of the message.
  - `message`: Content of the message.
  - `date`: Date and time of the message.
  - Additional time-based columns like `day_name`, `hour`, `minute`, etc.

## Dependencies 📦

The project requires the following libraries:

- **Streamlit**: Web framework for the dashboard.
- **Matplotlib**: For graphs and plots.
- **Seaborn**: For heatmaps and additional plotting.
- **Pandas**: For data manipulation and analysis.
- **WordCloud**: For generating word clouds.
- **Urlextract**: For URL extraction from the chat.
- **Emoji**: For analyzing emoji usage.

## Dependencies 📦
1.
   ```bash
   pip install -r requirements.txt

## Example 🖼️

Here's a preview of the analysis features:

- **Top Statistics**: Overview of total messages, words, media, and links.
- **Monthly and Daily Timelines**: Visualize message activity over time.
- **WordCloud**: Display most frequent words used in the chat.
- **Emoji Analysis**: Breakdown of frequently used emojis.

## Contributing 🤝

Feel free to fork the repository and make modifications. Contributions are welcome to enhance features or fix issues.


