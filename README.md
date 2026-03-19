# AI Studio

  A sophisticated multi-tool AI workspace powered by GPT-5.2.

  ## 4 Powerful Modes

  ### 💬 AI Chat
  6 expert personas: Research Assistant, Senior Dev, Creative Writer, Data Scientist, Tutor, Startup Advisor. Each has a tailored system prompt. Supports streaming responses with Markdown rendering.

  ### 📄 Text Analyzer
  Paste any text and get structured AI analysis:
  - 2-3 sentence summary
  - 5 key points (numbered)
  - Detected topics (tag chips)
  - Sentiment analysis (Positive/Negative/Neutral/Mixed)
  - 3 follow-up questions generated

  ### </> Code Review
  Paste code in any language (TypeScript, Python, Go, Rust, Java, SQL...) and receive:
  - Overall quality score (0-100)
  - Bug report with severity levels (high/medium/low) and code snippets
  - Security vulnerability analysis
  - Performance improvements
  - What's good (positives)
  - Summary assessment

  ### 🎨 Image Studio
  Text-to-image generation with 10 style presets:
  Photorealistic · Oil Painting · Watercolor · Digital Art · Anime · Sketch · 3D Render · Pixel Art · Cinematic · Minimalist

  ## Tech Stack
  React 19 · TypeScript · Tailwind CSS · Vite · OpenAI GPT-5.2 (chat + image)

  ## Getting Started
  ```bash
  npm install
  npm run dev
  ```
  Requires [portfolio-api-server](https://github.com/WebGhost01/portfolio-api-server) running on port 8080.