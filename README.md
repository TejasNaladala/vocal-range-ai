# vocal-range-ai

Say bye-bye to awkward "sing something for us" moments. This tool helps everyday singers discover their vocal range using AI-powered pitch detection, and recommends songs that match their voice. As someone who is a bathroom singer, I built this tool to help people like me science-backed suggestions for songs that fit their vocal range and to make them aware of their capabilities. So whether you’re a tenor or soprano, I hope vocal-range-ai helps you sing confidently :)

**Features:**

Real-time pitch detection from microphone input
Vocal range classification (e.g., Bass, Tenor, Alto, Soprano) along with pitch accuracy, vibrato, and vocal brightness
Expandable song database with vocal range metadata
Intelligent matching algorithm to recommend songs
Developed using Python with signal processing libraries like NumPy, SciPy, and librosa

**How It Works:**

1. Pitch Detection - Captures live audio input and extracts pitch using FFT/autocorrelation.
2. Range Analysis - Tracks your highest and lowest sustained notes to determine your vocal limits.
3. Vocal Range Classification - Maps your range to categories (e.g., Alto = G3–F5).
4. Smart Song Matching - Compares your range with metadata from a song database to suggest top matches.

**Libraries Used:**

`librosa`, `NumPy`, `SciPy` – signal processing
`sounddevice`, `pyaudio` – audio input
`matplotlib`, `plotly` – visualizations
`pandas`, `SQLite` – song metadata storage

**Setup Instructions:**

1. Clone the repo: git clone https://github.com/yourusername/vocal-range-ai.git then enter
2. Navigate to directory: cd vocal-range-ai
3. Install dependencies - pip install -r requirements.txt
4. Run the application - python src/main.py

**About Me:**

My name is Tejas Naladala and I am a freshman at the University of Washington, Seattle. I intend to pursue ECE. I love tinkering along the edge of hardware and software. My current interests include signal processing, audio tech, embedded AI, power electronics and photonics. I'd love to connect on linkedIn @www.linkedin.com/in/tejasnaladala :) 

Hope you like the project <3
