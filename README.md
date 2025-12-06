# A Game a Day — Ultra AI Edition

A beautiful, interactive web application that generates 30 days of unique game ideas with AI-powered creativity. Features a modern gradient UI, tabbed interface, and comprehensive idea management system.

## Features

### 🎮 Generator Tab
- Generate 30 days of unique game ideas (customizable 1-365 days)
- Optional title and description inputs to influence generation
- Real-time search to filter through generated ideas
- Export ideas as TXT, JSON, or CSV

### ⚡ Quick Idea Tab
- Instantly generate a single random game idea
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

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Python 3.x (for local server) or any static file server

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
- **LocalStorage** - Client-side data persistence

## Project Structure

```
A-Game-a-Day/
├── index.html          # Main application file
└── README.md           # This file
```

## Features in Detail

### Idea Generation
Each idea includes:
- **Genres**: 1-3 game genres (RPG, Platformer, Horror, etc.)
- **Setting**: Unique game world location
- **Mechanic**: Core gameplay mechanic
- **Story Hook**: Narrative premise
- **Title**: AI-generated title based on description

### Data Persistence
All data is stored locally in your browser using LocalStorage:
- Favorites persist across sessions
- Generation history is saved automatically
- Settings are remembered

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.

## Acknowledgments

- Inspired by game development challenges and creative exercises
- Built with modern web technologies for optimal performance

