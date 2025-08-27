# Moodify-AI-based-Music-Book-Movie-Recommender
 Project Overview
Moodify is an intelligent AI-powered recommendation system that leverages computer vision and deep learning to personalize entertainment content. By detecting a person’s face, age, and emotional state in real-time, the system recommends music, books, and movies that best fit the user’s mood and demographic profile.

The project begins with face detection using OpenCV, followed by emotion and age recognition using DeepFace. Based on these insights, the system uses curated datasets and the Google Books API to recommend age-appropriate and emotion-driven media. Recommendations are then displayed interactively, with direct links opened in the web browser.

Why This Project?
Instead of endless scrolling or generic suggestions, Moodify ensures that every recommendation is context-aware and personalized. It acts as a digital companion that understands your current state of mind and provides content to uplift, relax, or inspire you.

🚀 Features
🎥 Face Detection – Captures faces using OpenCV.

😀 Emotion Recognition – Detects user’s emotional state (happy, sad, angry, neutral, etc.).

🎂 Age Detection – Estimates user’s age group for appropriate recommendations.

🎶 Music Recommendations – Suggests songs/playlists based on detected mood.

📚 Book Recommendations – Uses Google Books API for relevant book suggestions.

🍿 Movie Recommendations – Suggests movies mapped to age and mood.

🌐 Interactive Outputs – Opens media links directly in the web browser.


🔧 Technologies Used
Python 3.9+

OpenCV – Face & age detection

DeepFace – Emotion recognition

Google Books API – Book recommendations

SpeechRecognition – Voice command support (optional)

Pandas & Numpy – Data handling

Webbrowser & Requests – Opening recommendations online


⚙️ How It Works
Face Capture → Webcam input is processed with OpenCV.

Feature Extraction → DeepFace predicts age and emotional state.

Recommendation Mapping:

Happy → Upbeat playlists, comedies, light novels.

Sad → Relaxing music, motivational books, inspiring films.

Angry → Calm songs, self-help books, peaceful movies.

Neutral → Trending/popular picks.

Interactive Output → Recommended media opens in the browser.


Practical Applications
🎧 Entertainment – Personalized playlists, books & movies.

🧠 Mental Wellness – Suggests calming or uplifting content.

👩‍🏫 Education – Age-appropriate book suggestions.

📺 OTT & Streaming – Smarter, mood-driven content recommendations.


📝 Example Output
Input: 23-year-old user detected, Emotion → Happy 😃

Output:

🎶 Recommended Song → “Uplifting Pop Playlist on YouTube”

📚 Recommended Book → “The Happiness Advantage – Shawn Achor”

🎬 Recommended Movie → “The Secret Life of Walter Mitty”


📌 Future Improvements
🔊 Voice-controlled recommendation support

🎵 Integration with Spotify & IMDb APIs

📱 Web & Mobile app deployment

📊 Advanced personalization using user history
