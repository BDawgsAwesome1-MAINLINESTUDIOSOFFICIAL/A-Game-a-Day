# A Game a Day — Ultra AI Edition

A beautiful, interactive web application that generates 30 days of unique game ideas with **real AI-powered creativity** using OpenAI's GPT models. Features a modern gradient UI, tabbed interface, and comprehensive idea management system. Works with or without an API key - falls back to intelligent random generation if no key is provided.

## Features

### 🎮 Generator Tab
- Generate 30 days of unique game ideas (customizable 1-365 days)
- **Real AI-powered generation** using OpenAI GPT models (GPT-4o, GPT-4o Mini, or GPT-3.5 Turbo)
- Optional title and description inputs to influence AI generation
- Falls back to intelligent random generation if no API key is provided
- Real-time search to filter through generated ideas
- Export ideas as TXT, JSON, or CSV

### ⚡ Quick Idea Tab
- Instantly generate a single game idea (AI-powered or random)
- Uses AI when API key is configured
- One-click favorite, copy, or share functionality

### ⭐ Favorites Tab
- Save your favorite game ideas
- Search through saved favorites
- Badge notification showing favorite count

### 📜 History Tab
- View all past generations
- Reload any previous generation
- Clear history option

### 📊 Stats Tab
- Total ideas generated
- Number of favorites
- Total generations count
- Most used genre analytics

### ⚙️ Settings Tab
- Configure number of days to generate (1-365)
- Set default export format (TXT, JSON, CSV)
- Toggle auto-save to history
- **OpenAI API Key configuration** - Add your API key for AI-powered generation
- **AI Model selection** - Choose between GPT-4o, GPT-4o Mini, or GPT-3.5 Turbo

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Python 3.x (for local server) or any static file server
- (Optional) OpenAI API key for AI-powered generation - Get one at [platform.openai.com/api-keys](https://platform.openai.com/api-keys)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/A-Game-a-Day.git
cd A-Game-a-Day
```

2. Start a local server:

**Using Python:**
```bash
python3 -m http.server 5000
```

**Using Node.js (if you have http-server installed):**
```bash
npx http-server -p 5000
```

3. Open your browser and navigate to:
```
http://localhost:5000
```

## Usage

### Basic Usage (Without API Key)
1. Open the app in your browser
2. Click "Generate Ideas" - uses intelligent random generation
3. All features work without an API key

### AI-Powered Usage (With API Key)
1. Go to the **Settings** tab
2. Enter your OpenAI API key (get one at [platform.openai.com/api-keys](https://platform.openai.com/api-keys))
3. Select your preferred AI model (GPT-4o Mini recommended for best balance)
4. Click "Save Settings"
5. Generate ideas - they'll now be AI-powered and more creative!

### General Features
1. **Generate Ideas**: Enter an optional title or description, then click "Generate Ideas"
2. **View Details**: Click any idea card to see the full explanation
3. **Save Favorites**: Click the star icon (☆) on any idea to favorite it
4. **Search**: Use the search box to filter ideas by keywords
5. **Export**: Download your ideas in your preferred format (TXT, JSON, or CSV)
6. **Quick Ideas**: Use the Quick Idea tab for instant inspiration

## Technology Stack

- **HTML5** - Structure
- **CSS3** - Styling with modern gradients and animations
- **Vanilla JavaScript** - No frameworks, pure JS
- **OpenAI API** - Real AI-powered game idea generation (GPT-4o, GPT-4o Mini, GPT-3.5 Turbo)
- **LocalStorage** - Client-side data persistence

## Project Structure

```
A-Game-a-Day/
├── index.html          # Main application file
└── README.md           # This file
```

## Features in Detail

### Idea Generation

**With AI (OpenAI API Key):**
- Uses GPT models to generate truly unique, creative game concepts
- AI understands context from your title/description inputs
- Generates original genres, settings, mechanics, and story hooks
- Creates cohesive game ideas with detailed explanations
- More creative and varied than random generation

**Without AI (Fallback Mode):**
- Intelligent random selection from curated lists
- Smart title generation based on description keywords
- Still produces interesting and varied ideas

Each idea includes:
- **Genres**: 1-3 game genres (RPG, Platformer, Horror, etc.)
- **Setting**: Unique game world location
- **Mechanic**: Core gameplay mechanic
- **Story Hook**: Narrative premise
- **Title**: AI-generated or smart-random title
- **Explanation**: Detailed description of the game concept

### Data Persistence
All data is stored locally in your browser using LocalStorage:
- Favorites persist across sessions
- Generation history is saved automatically (includes AI usage flag)
- Settings are remembered (including API key - stored securely in browser)
- **Note**: API keys are stored in browser LocalStorage only - never sent to any server except OpenAI

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## API Key Security

- API keys are stored **only in your browser's LocalStorage**
- Keys are **never sent to any server except OpenAI's API**
- Keys are **never committed to git or shared**
- You can clear your API key anytime in Settings
- The app works perfectly without an API key (uses intelligent random generation)

## Cost Information

When using OpenAI API:
- **GPT-4o Mini**: ~$0.15 per 1M input tokens, ~$0.60 per 1M output tokens (Recommended - best balance)
- **GPT-4o**: ~$2.50 per 1M input tokens, ~$10 per 1M output tokens (Highest quality)
- **GPT-3.5 Turbo**: ~$0.50 per 1M input tokens, ~$1.50 per 1M output tokens (Fastest)

Generating 30 ideas typically costs **$0.01 - $0.10** depending on the model.

## Acknowledgments

- Powered by **OpenAI GPT models** for real AI creativity
- Inspired by game development challenges and creative exercises
- Built with modern web technologies for optimal performance

