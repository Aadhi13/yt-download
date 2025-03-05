# YouTube Batch Video Downloader
A powerful bash script for batch downloading YouTube videos with advanced features and user-friendly interactions.

## 🚀 Features
- Multiple YouTube URL format support
- Batch download from text file
- Interactive directory selection
- Smart filename collision handling
- URL validation with user confirmation
- Configurable download options
- Automatic subtitle and metadata embedding

## 📋 Prerequisites
- Linux environment
- Python 3
- yt-dlp (`pip3 install yt-dlp`)

## 🔧 Installation
### Option 1: Direct Download
1. **Create Scripts Directory**
```bash
# Create bin directory if it doesn't exist
mkdir -p ~/bin
```

2. **Download Script**
```bash
# Download the script
curl -o ~/bin/yt-download https://raw.githubusercontent.com/Aadhi13/yt-download/master/yt-download
# Make the script executable
chmod +x ~/bin/yt-download
```

3. **Add to PATH**
```bash
# For Bash
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
# For Zsh
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```

### Option 2: Clone the Repository
1. **Clone the repository**
```bash
git clone https://github.com/Aadhi13/yt-download.git
```

2. **Create Scripts Directory**
```bash
# Create bin directory if it doesn't exist
mkdir -p ~/bin
```

3. **Copy the script to bin directory**
```bash
cp yt-download/yt-download ~/bin/
```

4. **Make the script executable**
```bash
chmod +x ~/bin/yt-download
```

## 📥 Usage
### Prepare Links File
Create a text file (`links.txt`) with YouTube URLs:
```
https://youtu.be/video1 [Optional Description]
https://youtube.com/watch?v=video2 [Another Description]
```

### Run the Script
```bash
yt-download links.txt
```

## 🛠️ Interactive Features
### Directory Selection
- Choose download location:
  - Default directory
  - Current directory
  - Custom path

### File Handling
- Handles existing files with options to:
  - Skip video
  - Automatically rename
  - Overwrite
  - Cancel download

### URL Validation
- Warns about non-standard URLs
- Allows proceeding or skipping

## 📦 Download Configuration
The script uses `yt-dlp` with advanced settings:
- Best available video quality
- MKV output format
- Embedded subtitles
- Metadata inclusion
- Thumbnail embedding

## 📄 License Rationale and Details
**Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**
### Why Creative Commons Attribution-NonCommercial-ShareAlike 4.0?

The license was carefully chosen to align with core open-source principles and the project's fundamental values:

- **Attribution (BY)**: Ensures proper credit is given to the original creator, preserving the project's lineage and acknowledging the initial effort.
- **NonCommercial (NC)**: Prevents commercial exploitation of the script, keeping it true to its community-driven origins.
- **ShareAlike (SA)**: Guarantees that derivative works remain open and accessible, continuing the spirit of collaborative development.

**Key Motivations:**
- Protect the script's open-source integrity
- Prevent commercial monetization
- Encourage community contributions
- Maintain transparency and attribution
- Ensure the project remains free and accessible

🚫 **Strict Guidelines:**
- No commercial selling of the script
- No proprietary software derivations
- Mandatory attribution to the original author
- All modifications must be shared under the same license

Full license details: [https://creativecommons.org/licenses/by-nc-sa/4.0/]

## 🤝 Contributing
Contributions, issues, and feature requests are welcome!

## 🔗 Repository
- **Author**: [Adhil Ameen](https://github.com/Aadhi13)
- **Repository**: [https://github.com/Aadhi13/yt-download]
