# OmniCreator

**AI-Powered Video Creation for macOS**

Transform scripts into professional videos with AI-generated content, text-to-speech narration, stock footage, and automated editing.

[![Download](https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge)](https://github.com/ComebackRay123/OmniCreator-Release/releases/latest)
[![Platform](https://img.shields.io/badge/Platform-macOS%2012.1%2B-lightgrey?style=for-the-badge)](https://github.com/ComebackRay123/OmniCreator-Release)
[![Architecture](https://img.shields.io/badge/Architecture-Apple%20Silicon-orange?style=for-the-badge)](https://github.com/ComebackRay123/OmniCreator-Release)

---

## 📥 Download

**Requirements**: macOS 12.1+ (Monterey or later) on Apple Silicon (M1/M2/M3)

**[⬇️ Download OmniCreator v1.0.0 (252 MB)](https://github.com/ComebackRay123/OmniCreator-Release/releases/latest)**

---

## ✨ Features

### 🎬 Complete Video Production Pipeline

#### 📝 **Script Generation & Management**
- **AI Script Generation** - Generate scripts with OpenAI GPT-4 or Google Gemini
- **Multi-Language Support** - Create scripts in multiple languages
- **Script Versions** - Manage different script versions for A/B testing
- **Real-Time Analysis** - Word count, duration estimation, readability scores
- **8-Minute Segment Markers** - Visual dividers for long-form content planning
- **Script Editor** - Full-featured text editor with formatting

#### 🎙️ **Text-to-Speech Audio Synthesis**
- **Multiple TTS Providers**:
  - Deepgram TTS - High-quality AI voices
  - ElevenLabs - Ultra-realistic voice cloning
  - Google TTS - Multi-language support
- **Voice Selection** - Choose from dozens of AI voices
- **Audio Preview** - Test voices before generating full project
- **Beat-Based Generation** - Generate audio for individual segments or entire project
- **Actual Duration Tracking** - Precise audio duration for perfect sync

#### 🎨 **Visual Content Acquisition**

**Stock Video Sources:**
- **Pixabay Integration** - Search and download free stock videos
- **Pexels Integration** - Access millions of high-quality videos
- **AI Query Generation** - Automatically generate search queries from script content
- **Manual Search** - Browse and select videos manually
- **Multi-Source Support** - Combine videos from different sources

**AI Image Generation:**
- **DALL-E 3** (OpenAI) - Photorealistic AI images
- **Gemini Imagen** (Google) - High-quality image synthesis
- **Stability AI** - Advanced image generation
- **Beat-Based Mode** - One image per audio segment (~45 images)
- **Scene-Based Mode** - One image per scene (~10 images, 75% cost savings)
- **Custom Prompts** - Full control over image generation prompts
- **Prompt Templates** - Save and reuse successful prompts

#### 🎬 **Scene Detection & Management**
- **AI Scene Detection** - Automatically identify scene boundaries from script
- **Visual Scene Editor** - Edit scene descriptions and prompts
- **Scene Preview** - Review scene breakdown before generation
- **Configurable Scene Count** - Adjust target number of scenes (8-12 recommended)
- **Scene-to-Beat Mapping** - Automatically assign scenes to audio beats

#### 🎞️ **Video Rendering & Effects**

**Rendering Features:**
- **Ken Burns Effects** - Automatic pan and zoom on images
- **Caption Rendering** - Customizable text overlays with multiple styles
- **Transitions** - Smooth transitions between clips
- **Background Music** - Mix background audio tracks
- **Multiple Resolutions** - 1080p, 1440p, 4K support
- **Frame Rate Options** - 24fps, 30fps, 60fps
- **Memory Management** - Optimized rendering for large projects
- **Stop/Resume** - Cancel rendering mid-process

**Output Formats:**
- Vertical (9:16) - Perfect for YouTube Shorts, TikTok, Instagram Reels
- Horizontal (16:9) - Standard YouTube videos
- Square (1:1) - Social media posts

#### 📤 **YouTube Integration**
- **OAuth2 Authentication** - Secure Google account linking
- **Direct Upload** - Upload videos straight to YouTube
- **Scheduled Publishing** - Cron-based scheduling (e.g., "0 9 * * 1" = every Monday 9am)
- **Playlist Management** - Add videos to playlists automatically
- **Channel Selection** - Upload to specific channels
- **Privacy Settings** - Public, Unlisted, or Private uploads

#### ✂️ **Video Clipping & Editing**
- **Long to Short Conversion** - Extract clips from long-form videos
- **Precise Trimming** - Frame-accurate start/end points
- **Format Conversion** - Convert between aspect ratios
- **Batch Processing** - Clip multiple segments at once

#### 📥 **Manual Video Downloader**
- **Direct Video Search** - Search Pixabay/Pexels without creating a project
- **Quick Downloads** - Save videos for later use
- **Preview Before Download** - Watch videos before downloading
- **Metadata Display** - View video duration, resolution, and source

#### 📚 **Content Library**
- **Topic Tracking** - Keep history of all created video topics
- **Duplicate Detection** - AI-powered similarity checking to avoid repeating content
- **Auto-Categorization** - 10 categories (Science, Technology, History, etc.)
- **Search & Filter** - Find topics by keyword, category, status, or date
- **Topic Suggestions** - AI-generated ideas based on your content history
- **Import Existing Projects** - Scan and import all past projects
- **Export/Import** - Backup and share your content library

#### ⚙️ **Settings & Configuration**

**API Key Management:**
- Encrypted storage with system keyring
- Support for all major AI providers
- Test API keys before use
- Separate keys for different features

**AI Provider Settings:**
- Model selection (GPT-4, GPT-3.5, Gemini Pro, etc.)
- Temperature and creativity controls
- Token limits and cost estimation
- Provider-specific options

**TTS Configuration:**
- Voice model selection
- Speed and pitch adjustments
- Language selection
- Preview before generation

**Video Configuration:**
- Output resolution and FPS
- Video codec selection
- Audio bitrate settings
- Caption style customization

**Dependency Checker:**
- Startup validation of FFmpeg and libraries
- System requirements verification
- Disk space monitoring
- Detailed diagnostic information

---

## 🚀 Quick Start Guide

### Installation

1. Download `OmniCreator-macOS-arm64.zip` from [Releases](https://github.com/ComebackRay123/OmniCreator-Release/releases/latest)
2. Extract the ZIP file
3. Move `OmniCreator.app` to `/Applications/`
4. Launch OmniCreator

### First-Time Setup

1. **Get API Keys** (choose at least one from each category):

   **AI Script Generation** (choose one or both):
   - [OpenAI API Key](https://platform.openai.com/api-keys) - For GPT-4/GPT-3.5 and DALL-E
   - [Google Gemini API Key](https://ai.google.dev) - For Gemini Pro and Imagen

   **Text-to-Speech** (choose one):
   - [Deepgram API Key](https://console.deepgram.com)
   - [ElevenLabs API Key](https://elevenlabs.io)
   - Google Gemini (same key as above)

   **Stock Video** (optional):
   - [Pixabay API Key](https://pixabay.com/api/docs/)
   - [Pexels API Key](https://www.pexels.com/api/)

2. **Configure OmniCreator**:
   - Open OmniCreator
   - Click **Keys** tab
   - Enter your API keys
   - Click **Save**

3. **Create Your First Video**:

   **Step 1: Generate Script**
   - Go to **Script** tab
   - Enter project name
   - Choose topic or enter custom prompt
   - Click **Generate Script** (or paste your own)

   **Step 2: Configure Workflow**
   - Go to **Workflow** tab
   - Select video source:
     - **Stock Videos** (Pixabay/Pexels) - For real footage
     - **AI Images (Beat-Based)** - One image per segment
     - **AI Images (Scene-Based)** - One image per scene (recommended)
   - If using Scene-Based:
     - Click **📽️ Scenes** to detect scenes
     - Review and edit scenes (optional)
     - Click **🎨 Generate Scene Images**

   **Step 3: Generate Audio**
   - Click **🎙️ Generate Audio for All Beats**
   - Wait for TTS synthesis to complete

   **Step 4: Render Video**
   - Go to **Render** tab
   - Configure caption style (optional)
   - Click **Render Video**
   - Wait for rendering to complete

   **Step 5: Upload (Optional)**
   - Go to **Upload** tab
   - Authenticate with YouTube
   - Configure upload settings
   - Click **Upload**

---

## 💡 Pro Tips

### Cost Optimization
- **Use Scene-Based Rendering**: Saves 75% on AI image generation costs
  - 45 beats = 45 images = $1.80
  - 45 beats = 10 scenes = $0.40

- **Mix Content Sources**: Combine stock videos with AI images for variety

- **Preview Voices**: Test TTS voices with short samples before generating full audio

### Performance
- **Close Other Apps**: Free up RAM for rendering
- **Monitor Disk Space**: Keep 10GB+ free for large projects
- **Use Simple Project Names**: Avoid special characters and emojis

### Quality
- **Edit Scene Prompts**: Refine AI image prompts for better results
- **Adjust Caption Timing**: Fine-tune caption display duration
- **Test Renders**: Render short segments first to verify settings

---

## 🎯 Use Cases

- **Educational Content** - Science explanations, history lessons, tutorials
- **YouTube Automation** - Scheduled uploads for consistent content
- **Vertical Videos** - Shorts, Reels, and TikTok content
- **Long-Form Content** - 8+ minute videos with segment markers
- **Multi-Language Content** - Create versions in different languages
- **Content Planning** - Track topics and avoid duplicates

---

## 📊 Technical Specifications

**Application:**
- Size: 625 MB (252 MB compressed)
- Framework: PyQt6
- Video Engine: MoviePy + FFmpeg 7.1
- Platform: macOS 12.1+ (Apple Silicon)

**Supported Formats:**
- **Video Output**: MP4 (H.264/H.265)
- **Audio Output**: WAV, MP3, AAC
- **Image Input**: PNG, JPG, WEBP
- **Video Input**: MP4, MOV, AVI

**Performance:**
- Rendering Speed: ~1-2 minutes per minute of video
- Memory Usage: 500MB - 2GB depending on project
- Disk Space: 5-10GB recommended for projects

---

## 🐛 Troubleshooting

### App Won't Launch
- Verify macOS version (12.1+)
- Check Apple Silicon architecture (M1/M2/M3)
- Right-click app → Open (bypass Gatekeeper on first launch)

### FFmpeg Not Found
- App includes bundled FFmpeg
- Check Settings → Dependencies for status
- Manual install: `brew install ffmpeg`

### Black Screens in Video
- Ensure all beats have audio generated
- Verify video/image paths exist in project folder
- Check render logs for errors

### Out of Memory
- Reduce project size (fewer beats)
- Lower output resolution
- Close other applications
- Restart OmniCreator

### API Errors
- Verify API keys are valid
- Check API rate limits
- Ensure sufficient API credits
- Test keys in Keys tab

---

## 📈 Roadmap

- [ ] Windows and Intel Mac support
- [ ] Additional AI providers (Anthropic Claude, etc.)
- [ ] Video templates and presets
- [ ] Collaborative editing
- [ ] Cloud rendering
- [ ] Mobile companion app

---

## 🙏 Acknowledgments

Built with [SoloDev](https://solodev.app) - AI-powered development assistant

---

## 📄 License

Proprietary - All rights reserved

---

**Version**: 1.0.0
**Last Updated**: November 2025
**Support**: For issues or questions, please open an issue on this repository
