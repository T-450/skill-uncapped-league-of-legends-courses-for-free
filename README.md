# skill-uncapped

[![License: MIT][]](https://opensource.org/licenses/MIT)

Script for viewing and downloading educational content from [Skill-Capped](https://www.skill-capped.com/).

<img width="1272" height="881" alt="image" src="https://github.com/user-attachments/assets/01f9f2f7-eacb-4ad4-90f5-e068e8e58f6e" />


## Features

- **Video Streaming**: HLS-based streaming with adaptive quality
- **Download Capability**: Save videos for offline viewing
- **Modern UI**: Clean, dark-themed interface with intuitive controls
- **Progress Tracking**: Real-time download progress with visual feedback
- **Keyboard Controls**: Convenient video playback shortcuts
- **Mobile Responsive**: Works seamlessly on all devices

## Quick Start

1. Clone the repository
2. Open `skill_capped.html` in your browser
3. Install a [CORS disabler extension](https://chromewebstore.google.com/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino?hl=en) (required for video access)
4. Togle the extension **ON** before trying to watch or download a video.
5. Paste a SkillCapped video URL and click "Stream"

## Video Player Controls

- **Space**: Play/Pause
- **←/→**: Seek 10 seconds backward/forward
- **F**: Toggle fullscreen

## Technical Details

### Prerequisites
- Modern web browser (Chrome recommended)
- CORS disabler browser extension
- Stable internet connection

### URL Format```
Valid: https://www.skill-capped.com/lol/commentaries/[video-id]
Invalid: https://www.skill-capped.com/lol/browse/course/[course-id]/[video-id]```

