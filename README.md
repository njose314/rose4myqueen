# The Rose Day Experience

A high-end, mobile-first interactive web app celebrating Rose Day with four cinematic phases and smooth touch-optimized gameplay.

## 🌹 Features

- **Phase 1: Cosmic Intro** - A romantic introduction with an interactive "YES" trap input
- **Phase 2: Petal Brush** - Canvas-based wipe effect to reveal a secret message
- **Phase 3: Thorn & Grace** - Reflex game with slider control to collect petals and avoid thorns
- **Phase 4: Finale** - Animated rose bloom with a romantic call-to-action

## 🎨 Design System

- **Color Palette**: Deep Crimson (#8B0000), Soft Cream (#FFFDD0), Charcoal (#121212)
- **Typography**: Playfair Display (Serif) for romantic text, Inter (Sans-serif) for UI
- **Animation**: Smooth 60fps animations optimized for mobile devices
- **Accessibility**: Full ARIA support, keyboard navigation, screen reader compatible

## 📱 Mobile Optimization

- Fixed viewport (no scrolling)
- All interactive elements in the "Thumb Zone" (bottom 60%)
- Touch-optimized controls with haptic feedback
- Responsive design for iOS and Android
- Smooth finger tracking and gesture support

## 🚀 Deployment

### GitHub Pages
1. Push the contents of this folder to your GitHub repository
2. Enable GitHub Pages in repository settings
3. Select the branch to deploy from
4. Your site will be live at `https://yourusername.github.io/repo-name`

### Direct Hosting
Simply serve the `index.html` file and its assets on any static hosting service:
- Netlify
- Vercel
- AWS S3 + CloudFront
- Any web server

## 📋 File Structure

```
.
├── index.html              # Main entry point
├── assets/                 # Compiled CSS and JavaScript
│   ├── index-*.css        # Tailwind CSS (minified)
│   └── index-*.js         # React app (minified)
├── __manus__/             # Analytics and tracking (optional)
└── README.md              # This file
```

## 🎮 Game Instructions

### Phase 1: Cosmic Intro
- Type anything in the input field
- No matter what you type, it will always say "YES"
- Press Enter or click "Confirm" to proceed

### Phase 2: Petal Brush
- Drag your finger or mouse across the screen
- Brush away the floating rose petals
- Reveal the secret message (requires 40% of petals cleared)
- Petals slowly float back down, so keep petting!

### Phase 3: Thorn & Grace
- Use the slider at the bottom to move your heart
- Collect falling pink petals for points
- Avoid red thorns (they cause screen shake)
- Every 5 petals collected, receive a compliment
- Game lasts 30 seconds

### Phase 4: Finale
- Watch the rose stem grow and bloom
- Read the romantic message
- Click "Claim your Rose Day Kiss" to complete the experience

## 💻 Browser Support

- Chrome/Chromium (latest)
- Safari (iOS 13+, macOS 10.15+)
- Firefox (latest)
- Edge (latest)

## ⚙️ Technical Details

- **Framework**: React 19 with TypeScript
- **Styling**: Tailwind CSS 4
- **Animations**: requestAnimationFrame (60fps)
- **Canvas**: HTML5 Canvas for particle effects and game mechanics
- **Touch**: Full touch event support with preventDefault for smooth interactions

## 🔧 Performance

- Optimized for 60fps animations
- Minimal JavaScript bundle size
- Efficient canvas rendering
- Touch event debouncing
- Smooth transitions and animations

## 📝 Accessibility

- Full ARIA labels and descriptions
- Keyboard navigation support
- Screen reader compatible
- High contrast text on backgrounds
- Clear instructions on every screen
- Haptic feedback for mobile devices

## 🎯 Tips for Best Experience

1. **Mobile**: Use on a smartphone for the best touch experience
2. **Landscape**: Rotate to landscape for more screen space
3. **Sound**: Enable device sound for toast notifications
4. **Vibration**: Enable haptic feedback for tactile feedback
5. **Full Screen**: Use full-screen mode for immersive experience

## 📄 License

Created with ❤️ for Rose Day 2026

---

**Enjoy the experience!** 🌹💕
