# 📚 English Learning App - Mobile Study Platform

A complete, mobile-optimized web application for learning English vocabulary and irregular verbs with an 8-week structured study plan.

## ✨ Features

- **📱 Mobile-First Design** - Optimized for smartphone use
- **🔄 Interactive Flashcards** - Tap-to-flip vocabulary and verb cards
- **📊 Progress Tracking** - Monitor words learned, verbs mastered, and study streaks
- **💾 Auto-Save** - All progress saved locally in browser
- **🌐 Offline Support** - Works without internet after first load
- **✅ Daily Checklists** - Stay organized with daily study goals
- **📝 Practice Areas** - Write and save practice sentences
- **🎯 8-Week Curriculum** - Structured learning path

## 📂 Project Structure

```
english-learning-app/
├── index.html          # Main application file (single-page app)
├── README.md           # This file
├── .gitignore         # Git ignore file
├── package.json       # Project metadata
└── docs/
    ├── DEPLOYMENT.md  # Deployment guide
    └── FEATURES.md    # Detailed features documentation
```

## 🚀 Quick Start

### Option 1: Open Locally

1. Clone or download this repository
2. Open `index.html` in any modern web browser
3. Start learning!

### Option 2: Run with a Local Server

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Then open http://localhost:8000
```

## 📱 Mobile Installation

### Add to Home Screen (Recommended)

**iOS (iPhone/iPad):**
1. Open the app in Safari
2. Tap the Share button (square with arrow)
3. Scroll down and tap "Add to Home Screen"
4. Tap "Add"

**Android:**
1. Open the app in Chrome
2. Tap the menu (⋮) in the top-right
3. Tap "Add to Home screen"
4. Tap "Add"

Now you have an app icon on your home screen!

## ☁️ Deployment Options

### Option 1: Netlify (Easiest - FREE)

1. **Sign up** at [netlify.com](https://netlify.com)
2. **Drag & drop** the entire `english-learning-app` folder
3. Your app is live! You get a URL like: `your-app.netlify.app`

**OR** using Netlify CLI:
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
cd english-learning-app
netlify deploy --prod
```

### Option 2: Vercel (FREE)

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
cd english-learning-app
vercel
```

### Option 3: GitHub Pages (FREE)

1. Create a GitHub repository
2. Push this code to the repository
3. Go to Settings → Pages
4. Select branch: `main`, folder: `/ (root)`
5. Your app will be live at: `https://username.github.io/repo-name`

### Option 4: Cloudflare Pages (FREE)

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. Connect your GitHub repository
3. Deploy automatically

## 🛠️ Development

This is a single-page application with no dependencies. Everything you need is in `index.html`.

### Customization

To customize the app:

1. **Add more vocabulary**: Edit the `week1Vocabulary` array in the JavaScript section
2. **Add more weeks**: Create `week2Vocabulary`, `week3Vocabulary`, etc.
3. **Change colors**: Modify the CSS gradient values
4. **Add features**: The code is well-commented for easy modification

### File Structure

The `index.html` file contains three main sections:
- **CSS** (lines ~20-700): All styling
- **HTML** (lines ~700-1200): Page structure
- **JavaScript** (lines ~1200-end): App logic and data

## 📚 Content Included

### Week 1 Vocabulary (15 words)
Daily Routines & Home:
- wake up, get up, brush, shower, breakfast
- commute, lunch, break, dinner, relax
- homework, tired, early, late, routine

### Week 1 Irregular Verbs (5 verbs)
- be → was/were → been
- have → had → had
- do → did → done
- go → went → gone
- get → got → got

## 🎯 Learning Path

**Daily Study Routine (20-30 minutes):**
- Morning (10 min): Review 5-10 flashcards
- Afternoon (15 min): Practice verbs, write 3 sentences
- Evening (5 min): Review difficult cards, check progress

**Weekly Goals:**
- Week 1: Daily Routines & Home
- Week 2: Food & Restaurants
- Week 3: Work & Office
- Week 4: Travel & Transportation
- Weeks 5-8: Advanced topics

## 🔧 Technical Details

- **Technology**: Pure HTML5, CSS3, and Vanilla JavaScript
- **Storage**: LocalStorage API for progress tracking
- **Compatibility**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Size**: ~50KB total (very lightweight)
- **Performance**: Instant loading, no external dependencies

## 📖 Usage Guide

### Navigation
- Use the bottom navigation bar to switch between sections
- **Today** (🎯): Daily goals and checklist
- **Vocab** (📚): Vocabulary flashcards
- **Verbs** (✍️): Irregular verb practice
- **Progress** (📈): Statistics and achievements
- **Plan** (📋): 8-week study plan

### Flashcards
- Tap any card to flip and see the meaning
- Use "Next Card" to move forward
- Use "I know this word" to mark progress
- Progress auto-saves after each interaction

### Practice Area
- Write sentences using new vocabulary
- Save your practice for later review
- Practice is saved locally and persists between sessions

## 🤝 Contributing

This is a personal learning project. Feel free to fork and customize for your needs!

## 📄 License

Free to use and modify for personal learning purposes.

## 🆘 Support

### Common Issues

**Q: My progress isn't saving**
A: Make sure you're not in Private/Incognito mode. LocalStorage doesn't persist in private browsing.

**Q: The app looks broken on my phone**
A: Make sure you're using a modern browser (Chrome, Safari, Firefox). Clear your browser cache and reload.

**Q: Can I access this offline?**
A: Yes! After loading once, the app works completely offline. Add it to your home screen for best experience.

**Q: Can I add my own vocabulary?**
A: Yes! Open `index.html` in a text editor and modify the `week1Vocabulary` array. See the Customization section above.

## 🎓 Study Tips

1. **Be consistent**: Study 20-30 minutes daily rather than 3 hours once a week
2. **Use context**: Always read the example sentences, don't just memorize words
3. **Write daily**: Use the practice area to write your own sentences
4. **Review regularly**: Revisit old words every few days
5. **Track progress**: Check your statistics to stay motivated

## 📞 Contact

For questions or suggestions about deployment, create an issue or contact the developer.

---

**Happy Learning! 🚀**

Start your English learning journey today and track your progress towards fluency.
