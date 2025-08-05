# Viral AI

Transform one idea into viral content for multiple social media platforms using GPT-4 and OpenAI Vision API. Enter your idea, upload images, and get AI-generated content optimized for Twitter, LinkedIn, Instagram, and TikTok.

## ✨ Features

- **🤖 AI-Powered Generation**: GPT-4 integration for intelligent content creation
- **📸 Instagram Image Analysis**: OpenAI Vision API for image analysis and caption suggestions
- **🎯 Platform-Specific Optimization**: Each platform gets tailored content with appropriate tone
- **📱 Instagram Carousel Planning**: Upload, arrange, and plan multi-image posts
- **⚙️ Customizable AI Settings**: Configure tone, target audience, and generation preferences
- **📋 Copy-to-Clipboard**: Easy copying of generated content for each platform
- **🎨 Drag & Drop Interface**: Intuitive image upload and arrangement
- **📊 Real-time Analysis**: Instant AI-powered image and content analysis
- **📱 Responsive Design**: Works perfectly on desktop and mobile devices

## 🚀 Supported Platforms

### Twitter Thread
- Multi-tweet thread format
- Engaging hooks and call-to-actions
- Character count optimization
- Emoji and formatting for engagement

### LinkedIn Post
- Professional tone and structure
- Industry-focused language
- Thought leadership positioning
- Professional hashtags

### Instagram Caption & Carousel
- Visual and engaging content
- AI-powered image analysis
- Carousel planning and arrangement
- Hashtag optimization
- Call-to-action prompts
- Emoji integration
- Individual image captions

### TikTok Video Ideas
- Viral-worthy content concepts
- Trending elements and hooks
- Platform-specific optimization
- Engagement-focused structure

## 🛠️ Tech Stack

- **React 18** - Modern React with hooks
- **TypeScript** - Type-safe development
- **Tailwind CSS** - Utility-first styling
- **Vite** - Fast build tool and dev server
- **OpenAI GPT-4** - AI content generation
- **OpenAI Vision API** - Image analysis
- **React Dropzone** - Drag & drop file uploads
- **React Hot Toast** - User notifications
- **Lucide React** - Beautiful icons

## 📦 Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd viral-ai
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

## 🎯 Usage

### Basic Usage
1. **Configure AI Settings**: Enable AI and add your OpenAI API key
2. **Enter Your Idea**: Type your main idea or topic in the input field
3. **Upload Images** (Optional): Drag & drop images for Instagram carousel
4. **Generate Content**: Click the "Generate Multi-Platform Content" button
5. **Analyze Images** (Optional): Use AI to analyze uploaded images for captions
6. **Review Results**: Browse through the generated content for each platform
7. **Copy & Customize**: Copy the content and customize it for your brand voice

### AI Features
- **Content Generation**: GPT-4 creates platform-specific content
- **Image Analysis**: Vision API analyzes uploaded images and suggests captions
- **Tone Customization**: Choose from professional, casual, enthusiastic, or educational
- **Audience Targeting**: Select your target audience for better content relevance

## 📝 Example

**Input**: "Productivity hacks for remote workers"

**Outputs**:
- **Twitter**: AI-generated 5-tweet thread about remote work productivity
- **LinkedIn**: Professional post with thought leadership insights
- **Instagram**: Engaging caption with AI-analyzed hashtags and image captions
- **Blog**: Comprehensive introduction optimized for SEO and engagement

## 🔧 Development

### Project Structure
```
src/
├── components/
│   ├── ContentGenerator.tsx    # Main generator logic with AI integration
│   ├── ContentOutput.tsx       # Display generated content
│   ├── Header.tsx             # App header
│   ├── IdeaInput.tsx          # Input form
│   ├── InstagramImageUpload.tsx # Image upload and carousel planning
│   └── AIConfigPanel.tsx      # AI configuration settings
├── services/
│   └── openai.ts              # OpenAI API integration
├── types/
│   └── index.ts               # TypeScript definitions
├── App.tsx                    # Main app component
├── main.tsx                   # Entry point
└── index.css                  # Global styles
```

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build

## 🎨 Customization

### AI Configuration
- **API Key**: Add your OpenAI API key in the AI Configuration panel
- **Tone Settings**: Choose from professional, casual, enthusiastic, or educational
- **Target Audience**: Select your specific audience for better content relevance
- **Content Templates**: Customize prompts in `src/services/openai.ts`

### Instagram Features
- **Image Upload**: Drag & drop up to 10 images for carousel posts
- **Image Analysis**: AI analyzes images and suggests captions
- **Carousel Planning**: Arrange images in the perfect order
- **Individual Captions**: Add custom captions for each image

### Content Generation
The content generation logic is located in `src/components/ContentGenerator.tsx`. You can customize:
- Content templates and structure
- Platform-specific formatting
- Tone and voice adjustments
- Hashtag strategies
- AI prompt engineering

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Add tests if applicable
5. Submit a pull request

## 📄 License

MIT License - see LICENSE file for details

## 🙏 Acknowledgments

- Built with modern React patterns
- Styled with Tailwind CSS
- Powered by OpenAI GPT-4 and Vision API
- Icons from Lucide React
- Inspired by content creators and marketers
- Drag & drop functionality with React Dropzone

---

**Ready to transform your ideas into multi-platform content? Start generating! 🚀** 