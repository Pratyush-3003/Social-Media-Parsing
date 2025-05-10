📷 Instagram User Scraper & Media Analyzer
This project is a Streamlit-based web application that allows users to scrape and analyze public Instagram profiles. Enter a username, and the app will retrieve detailed profile information, along with the top 5 videos and images posted by the user — all in a clean, interactive dashboard.

🚀 Features
🔍 Scrape any public Instagram profile by username

📊 Display detailed user profile information: bio, category, followers, email, phone, etc.

🎥 Extract top 5 videos and images, including:

Likes, comments, captions, tagged users, timestamps, locations, etc.

📁 Sort media by likes, comments, or date

🖼️ View profile image and media thumbnails

📥 Download image/video data as JSON

⚙️ Robust error handling and responsive UI

🛠️ How It Works
Uses httpx to query Instagram’s internal API (https://i.instagram.com/api/v1/users/web_profile_info/)

Parses the JSON response to extract user profile details and recent posts

Displays data through a Streamlit interface

Allows sorting of media and exporting results

📦 Libraries Used
streamlit	
httpx
json
PIL
time
BytesIO
