# RunThru - AI-Powered QA Screen Recording Agent - OpeAI Hack - 4th Rank 

https://www.runthru.co/

<img width="1540" alt="Screenshot 2025-06-12 at 5 45 55 PM" src="https://github.com/user-attachments/assets/83951a20-813d-4f78-8ba5-90a26a3cd418" />


<img width="630" alt="Screenshot 2025-06-12 at 6 18 53 PM" src="https://github.com/user-attachments/assets/515fa7d8-9e26-4bb2-ab54-87c34841004b" />



# 🎥 AI-Powered Demo Video Generator

An intelligent system that **automatically creates demo videos** by executing web user flows with **screen recording** and **synthetic narration** capabilities.

---

## 🚀 Features

- 🧠 **AI Test Generation** – Powered by GPT-4o to convert natural language into structured test steps  
- 🧪 **Automated Browser Control** – Uses Playwright for robust and repeatable test flows  
- 🎥 **Screen Recording** – Captures crisp video of each step in the testing workflow  
- 🗣️ **AI Narration** – Auto-generates professional voiceovers with OpenAI TTS  
- 🎬 **Video Composition** – Creates polished demo videos with avatar overlay and synchronized audio  
- 📡 **Real-time Progress** – WebSocket-based live status updates during test execution  

---

## 🛠️ Core Technologies

| Layer             | Tools & Frameworks                                                                 |
|------------------|-------------------------------------------------------------------------------------|
| 💻 **Frontend**   | React, Vite ⚡, TypeScript, TailwindCSS                                              |
| 🧰 **Backend**    | Express.js with TypeScript                                                          |
| 🧠 **AI**         | OpenAI GPT-4o for test generation + narration, OpenAI TTS for voiceovers            |
| 🧪 **Automation** | Playwright for cross-browser automation                                             |
| 🎞️ **Video**      | FFmpeg for video composition and editing                                            |
| 🔌 **Live Sync**  | WebSocket for real-time session updates                                             |

---

## 📦 Getting Started

```bash
# Install dependencies
npm install

# Start the development server
npm run dev

## Quick Start

1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Set Environment Variables**
   ```bash
   OPENAI_API_KEY=your_openai_api_key
   ```

3. **Start Development Server**
   ```bash
   npm run dev
   ```

4. **Access the Application**
   Open http://localhost:5000 in your browser

## Usage

1. **Enter Website URL**: Provide the target website for testing
2. **Describe Test Scenario**: Use natural language to describe what you want to test
3. **Generate Recording**: The system will:
   - Generate detailed test steps using AI
   - Execute browser automation with screen recording
   - Create professional narration script
   - Generate voiceover using OpenAI's text-to-speech
   - Compose final video with audio and visual elements

## Example Test Scenarios

- "Test the user registration flow by creating a new account and verifying email confirmation"
- "Navigate to the marketplace, browse profiles, and complete a booking process"
- "Test the checkout flow with form validation and payment processing"

## Architecture

- **Input Processing**: AI-powered interpretation of test requirements
- **Browser Automation**: Playwright-driven test execution with screen capture
- **Narration Generation**: OpenAI-generated scripts and synthetic voice
- **Video Composition**: FFmpeg-powered video editing with avatar overlays
- **Real-time Updates**: WebSocket communication for progress tracking

## API Endpoints

- `POST /api/recordings/generate-steps` - Generate test steps from description
- `POST /api/recordings` - Create new recording session
- `POST /api/recordings/:id/start` - Start recording execution
- `GET /api/recordings/:id/download` - Download completed video

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

MIT License - see LICENSE file for details
