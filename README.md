# TanvirAI

> An intelligent AI-powered portfolio assistant built with modern web technologies

TanvirAI is a sleek, conversational interface that serves as a dynamic portfolio assistant for Syed Tanvir Islam. It leverages the Groq API to provide real-time, intelligent responses about projects, skills, and professional experience with a native-feeling, modern UX.

## ✨ Features

- **Real-time Conversational AI** - Powered by Groq's LLaMA 3.3-70B model for intelligent, context-aware responses
- **Markdown Rendering** - Full markdown support for formatted responses (code blocks, bold text, links, lists)
- **Typewriter Effect** - Natural, animated text streaming for better visual feedback
- **Responsive Design** - Optimized for desktop and mobile devices
- **Dark Theme** - Modern, eye-catching dark interface with custom color scheme
- **Smart Suggestions** - Quick-start prompt cards for first-time visitors
- **Conversation History** - Maintains context across multiple exchanges

## 🎯 What TanvirAI Can Help With

TanvirAI can assist with inquiries about:
- **Skills & Tech Stack** - Frontend technologies, frameworks, and tools
- **Project Showcase** - TanvirAI, DebateAI, Mr.Premium and other deployments
- **Professional Background** - Experience, achievements, and approach to development
- **General Questions** - Tech discussions, design principles, coding advice
- **Contact Information** - How to reach out for collaborations

## 🎮 Live Demo

**Try TanvirAI now:** https://syedtanvir.netlify.app/projects/tanvirai

Launch the app directly in your browser with no installation required!

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Active internet connection (for API calls)

### Usage

1. **Open the Application**
   ```bash
   # Simply open the HTML file in your browser
   open tanvirai.html
   ```

2. **Interact with TanvirAI**
   - Type your question in the input field
   - Press Enter or click the send button
   - TanvirAI responds in real-time with styled, formatted text

3. **Start with Suggestions**
   - Use the suggested prompt cards on the welcome screen
   - Try asking about Skills, Projects, or Contact information

## 🛠️ Technology Stack

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables, gradients, and animations
- **JavaScript** - DOM manipulation, event handling, async/await

### API & Backend
- **Groq API** - LLaMA 3.3-70B model for AI responses
- **OpenAI-Compatible Endpoints** - Seamless API integration

### Design System
- **Fonts** - Inter (body), Space Grotesk (display)
- **Color Scheme** - Custom dark theme with sage green accents
- **Design Pattern** - Modern minimal with glassmorphism effects

## 📋 Project Structure

```
tanvirai.html
├── HTML Structure
│   ├── Header with branding
│   ├── Main content area with welcome screen
│   ├── Messages container for conversation
│   └── Input region with text field and send button
├── CSS Styling
│   ├── Custom design tokens (colors, spacing, typography)
│   ├── Component styles
│   ├── Animations and transitions
│   └── Responsive layout
└── JavaScript Logic
    ├── API integration with Groq
    ├── Message handling and formatting
    ├── Markdown parsing
    ├── State management
    └── Event listeners
```

## 🎨 Customization

### Change the Brand Name
Update the brand text and colors in the HTML:
```html
<div class="brand">
    <div class="status-dot"></div>
    Your Brand Name
</div>
```

### Update the System Prompt
Modify the system prompt in the JavaScript section to change AI personality and knowledge base:
```javascript
{ 
    role: "system", 
    content: `Your custom system prompt here...`
}
```

### Adjust Theme Colors
Edit CSS variables in the `:root` selector:
```css
:root {
    --primary: #AEB784;        /* Main accent color */
    --bg-body: #050505;        /* Background */
    --text-main: #ededed;      /* Primary text */
    /* ... more variables ... */
}
```

## 🔑 Configuration

### API Setup
The application requires a Groq API key:

1. Get your API key from [console.groq.com](https://console.groq.com)
2. Replace the `API_KEY` in the script section (keep it secure in production!)
3. Optionally, modify the `API_URL` and model selection

```javascript
const API_KEY = 'your-groq-api-key';
const API_URL = 'https://api.groq.com/openai/v1/chat/completions';
```

## 🎯 Use Cases

- **Personal Portfolio** - Showcase projects and skills interactively
- **Customer Support** - Build domain-specific knowledge assistants
- **Educational Tool** - Help students learn with AI guidance
- **Business Assistant** - Create branded AI companions for businesses

## 🌟 Key Features Explained

### Typewriter Effect
Text streams word-by-word with slight delays for a natural conversation feel, making the AI responses feel more human-like and engaging.

### Markdown Parsing
Responses support:
- **Bold text**: `**text**`
- Code blocks: ` ``` ```
- Inline code: `` `code` ``
- Lists and line breaks

### Conversation Context
The system maintains full conversation history, allowing TanvirAI to provide contextual responses that remember previous messages.

### Responsive Layout
The interface adapts smoothly to different screen sizes while maintaining visual fidelity and usability across all devices.

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔒 Security Notes

- **API Key**: The API key is currently embedded in the client-side code. For production use, implement a backend proxy to securely handle API calls
- **Rate Limiting**: Consider implementing rate limiting on the backend to prevent abuse
- **Input Validation**: Always validate and sanitize user inputs

## 🚀 Performance Tips

- The application loads instantly as a single HTML file
- API response times depend on Groq's service (typically < 2 seconds)
- Markdown parsing and rendering is optimized for responsiveness
- CSS animations use GPU acceleration for smooth performance

## 🤝 Contributing

For improvements or customizations:
1. Fork or clone the repository
2. Modify the HTML file as needed
3. Test across different browsers
4. Deploy with your preferred hosting service

## 📄 License

This project is open source and available for personal and commercial use. Attribution appreciated!

## 👤 About the Creator

**Syed Tanvir Islam**
- 16-year-old self-taught frontend developer
- Location: Dhaka, Bangladesh
- Email: syedtanvirislam20@gmail.com
- GitHub: [@syedtanvircodex](https://github.com/syedtanvircodex)
- Philosophy: *Every detail matters.*

---

Built with ❤️ for seamless AI conversations
