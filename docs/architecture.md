Architecture Overview

System Flow

User → API → AI Script Generator → TTS → Clip Selector → FFmpeg → Output Video

Components

Frontend

- Next.js dashboard
- Project creation UI

Backend

- FastAPI server
- Handles API requests
- Controls video pipeline

Worker

- Executes FFmpeg tasks
- Handles video rendering

Storage

- Stores generated videos
- Stores temporary assets

Pipeline

1. Input topic or trend
2. Generate script
3. Generate voice
4. Select gameplay clip
5. Merge video + audio
6. Add captions and effects
7. Export final video
