# Tavus Avatar Agent

A LiveKit-powered educational AI agent that uses the Tavus.
## Installation
pip install -r requirements.txt
   ```

## Configuration
`.env` file:

```
OPENAI_API_KEY=your_openai_key
ELEVENLABS_API_KEY=your_elevenlabs_key
DEEPGRAM_API_KEY=your_deepgram_key
TAVUS_API_KEY=your_tavus_key
LIVEKIT_API_KEY=your_livekit_key
LIVEKIT_API_SECRET=your_livekit_secret
```

Run the agent with:

python tavus.py dev
```

### Frontend Setup

1. Navigate to the frontend directory:
   ```
   cd voice-assistant-frontend
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Start the development server:
   ```
   npm run dev