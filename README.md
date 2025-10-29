🏆 Project Title

AI-Powered Cinematic Wedding Video Creator

🎯 Overview

This project uses AI and video processing techniques to automatically combine multiple raw wedding clips into a single cinematic highlight video.
It enhances video tone, applies natural color grading, and merges multiple background music tracks for a professional cinematic experience.

🧠 Key Features

🎬 Automatically merges short clips into one seamless video.

🎨 Applies a cinematic color filter (natural tone, no orange-blue tint).

🎵 Combines multiple music tracks to avoid silence or mismatched endings.

🪄 Smooth transitions between clips using fade effects.

⚙️ Adjustable duration and tone strength.

🛠️ Tools & Libraries Used

Python

MoviePy — for video editing, transitions, and filters

NumPy — for pixel-level image operations

TQDM — for progress tracking

Google Colab — for model training and processing environment

(Optional: ffmpeg — backend support for video encoding)

📂 Dataset Structure
wedding_Dataset/
 ├── Dataset/
 │   ├── clip1.mp4
 │   ├── clip2.mp4
 │   ├── clip3.mp4
 │   └── ...
 └── music/
     ├── song1.mp3
     ├── song2.mp3
     └── song3.mp3

🚀 How It Works

All raw video clips are preloaded from the dataset.

The model applies a cinematic filter using color correction and contrast balancing.

Multiple songs are concatenated or mixed to create a continuous background track.

Videos are merged with smooth transitions and synchronized with music.

The final cinematic highlight video is exported.

💡 Future Improvements

Automatic scene detection and emotional music matching.

Face detection to focus on main subjects.

Addition of motion stabilization and slow-motion effects.

👩‍💻 Contributors

Tanu Kumari Dhillod,
Anshika Garg,
Khushi
