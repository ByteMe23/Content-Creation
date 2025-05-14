# Content-Creation

Content Creation is a next-generation web application that empowers users to create high-quality, professional-looking videos effortlessly. Powered by cutting-edge AI technologies and integrated with video processing tools, VidAI streamlines the entire video production workflow—from script generation to final export.

Built using **React**, **Next.js**, and **FFmpeg.js**, this platform is ideal for content creators, educators, marketers, and social media managers looking to automate and simplify video creation.

## Key Features

### AI-Powered Video Generation
- **Script Generation**: Turn your ideas into compelling video scripts using OpenAI's advanced language models.
- **Voiceover Creation**: Automatically synthesize high-quality voiceovers using ElevenLabs' text-to-speech engine.
- **Visual Generation**: Leverage AI to generate relevant and visually appealing images that align with your video narrative.

### Intelligent Video Editing
- **Automatic Assembly**: Combine images, voiceovers, transitions, and effects to create a seamless video experience.
- **Subtitles & Captions**: Add animated, customizable subtitles to improve accessibility and viewer engagement.
- **Smooth Transitions**: Apply professional-grade transition effects between video segments.
- **Background Music**: Easily add atmospheric background tracks to enhance mood and storytelling.

### Specialized Video Formats
- **TikTok / Reels Format**: Create vertically optimized videos tailored for TikTok, Instagram Reels, and YouTube Shorts.
- **Chat Simulation Videos**: Simulate messaging or texting conversations to create storytelling-based videos.
- **Reddit Story Narratives**: Automatically convert Reddit posts into engaging visual narratives.

## Getting Started

### Prerequisites
Ensure the following are installed:
- Node.js v18+
- FFmpeg (included via ffmpeg.js, no manual installation needed)

### Installation

1. ## Clone the Repository:

```bash
git clone https://github.com/yourusername/Content-Creation.git
cd Content-Creation
```

2. ## Install Dependencies:

```bash
npm install
```

3. ## Set up environment variables: Create a .env.local file in the root directory with the following variables:

```bash
OPENAI_API_KEY=your_openai_api_key
ELEVENLABS_API_KEY=your_elevenlabs_api_key
DEEPINFRA_API_KEY=your_deepinfra_api_key
```

4. ## Start the Development server:

```bash
npm run dev
```

5. Open your browser and navigate to http://localhost:3000

## Tech Stack

Frontend:
- React
- Next.js
- Tailwind CSS

Video Processing:
- FFmpeg.js
- VideoContext

AI Services:
- OpenAI: Script generation and text processing
- ElevenLabs: Text-to-speech and voice synthesis
- DeepInfra: Image generation

## How It Works

1. Script Generation: Input your idea, and the AI creates a compelling script for your video.
2. Audio Creation: The system automatically generates voiceovers for your script.
3. Visual Elements: AI generates images that match your story segments.
4. Video Assembly: FFmpeg combines all elements into a seamless video with transitions.
5. Customization: Add subtitles, music, and effects to enhance your video.
6. Export: Download your video and share it on social media platforms.

## Use Cases

- Content Creators: Quickly create engaging videos without extensive editing knowledge.
- Social Media Managers: Generate platform-specific content in minutes.
- Educators: Create educational content with clear narration and visuals.
- Marketers: Develop promotional videos with minimal effort.






