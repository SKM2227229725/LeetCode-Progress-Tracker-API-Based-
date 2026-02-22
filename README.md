LeetCode Progress Tracker (API-Based)

This  is simple web application .using  the HTML ,css,js used to fetches and visualizes LeetCode user statistics using the LeetCode GraphQL API. The application allows users to enter a LeetCode username and view detailed problem-solving insights in an interactive dashboard.

🚀 Features

Fetch total problems solved

Difficulty-wise breakdown (Easy / Medium / Hard)

Interactive bar chart visualization

Real-time data using LeetCode GraphQL API

Simple and clean Streamlit dashboard and etc

🛠 Tech Stack

HTML

 CSS
JS

📊 How It Works

The application sends a POST request to LeetCode’s GraphQL endpoint, retrieves submission statistics for a given username, processes the JSON response, and displays structured insights along with visual charts.

▶️ Installation & Run
git clone https://github.com/your-username/leetcode-progress-tracker.git
cd leetcode-progress-tracker
pip install -r requirements.txt
streamlit run app.py
