# Spotify_Gemini

A sample Python script that fetches your liked Spotify tracks and processes them.

## Table of Contents

- [Overview](#overview)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Overview

This project uses the Spotipy library to retrieve all your “Liked Songs” from Spotify and perform custom processing. It authenticates via environment variables and caches your OAuth token in `.spotify_cache`.

## Installation

1. **Clone the repo**  
   ```bash
   git clone https://github.com/Sebnemalural/Spotify_Gemini.git
   cd Spotify_Gemini

2. **Create & activate a virtual environment**

python -m venv .venv
# Windows
.\.venv\Scripts\Activate
# macOS/Linux
source .venv/bin/activate

3. **Install dependencies**

pip install -r requirements.txt

4. **Configure environment variables**

# Windows
copy .env.example .env

# macOS/Linux
cp .env.example .env



