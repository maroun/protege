# GIS Tools Instagram Animation 🌍✨

An animated Instagram story/reel showcasing different GIS tools and their pricing models.

## Overview

This is a 25-second animated presentation designed for Instagram, featuring:
- **Scene 1 (0-3s)**: Intro with spinning globe
- **Scene 2 (3-12s)**: 8 GIS tools carousel with animated cards
- **Scene 3 (12-18s)**: Budget-friendly vs Pro-level recommendations
- **Scene 4 (18-21s)**: Pro tip for mixing tools
- **Scene 5 (21-25s)**: Outro with hashtags

## How to View

1. Open `index.html` in a modern web browser (Chrome, Firefox, Safari, or Edge)
2. The animation will start automatically
3. Click anywhere to restart the animation

## Recording for Instagram

### Method 1: Screen Recording (Recommended)

**For macOS:**
1. Open the HTML file in a browser (preferably Chrome in full screen)
2. Press `Cmd + Shift + 5` to open screen recording
3. Select the browser window
4. Click "Record"
5. Wait for the 25-second animation to complete
6. Stop recording and save the video

**For Windows:**
1. Open the HTML file in a browser
2. Press `Windows + G` to open Xbox Game Bar
3. Click the record button
4. Wait for the animation to complete
5. Stop recording (Windows + Alt + R)

**For Linux:**
- Use tools like `SimpleScreenRecorder` or `OBS Studio`

### Method 2: Browser Extensions

Use browser extensions like:
- **Loom** (Chrome/Edge)
- **Screencastify** (Chrome)
- **Nimbus Screenshot & Screen Video Recorder** (Chrome/Firefox)

### Method 3: Online Tools

1. Upload the HTML file to a web server or GitHub Pages
2. Use online screen recorders like:
   - Screencast-O-Matic
   - Apowersoft Free Online Screen Recorder

## Converting to Instagram Format

Instagram Stories/Reels specifications:
- **Resolution**: 1080x1920 (9:16 aspect ratio) ✅ Already optimized!
- **Duration**: 15-60 seconds ✅ 25 seconds fits perfectly
- **Format**: MP4 or MOV

### Video Editing (if needed)

After recording, you can use video editing tools to:
1. **Trim** the video to exactly 25 seconds
2. **Add background music** (Instagram has a library)
3. **Adjust quality** for better compression

Recommended tools:
- **Free**: CapCut, iMovie, DaVinci Resolve
- **Online**: Kapwing, Clideo
- **Professional**: Adobe Premiere Pro, Final Cut Pro

## Customization

You can easily customize the animation by editing `index.html`:

### Colors
The gradient colors can be changed in the CSS:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Timing
Adjust scene timing in the JavaScript `sceneTiming` array:
```javascript
const sceneTiming = [
    { scene: 1, start: 0, end: 3 },
    { scene: 2, start: 3, end: 12 },
    // ... etc
];
```

### Tools
Modify the tools array to add/remove/edit GIS tools:
```javascript
const tools = [
    {
        icon: '🏆',
        name: 'ArcGIS',
        desc: 'Subscription + Student Licenses',
        color: '#0079c1',
        burst: false
    },
    // ... etc
];
```

### Text Content
All text can be edited directly in the HTML sections.

## Features

✅ Smooth CSS animations and transitions
✅ Optimized for Instagram Stories (1080x1920)
✅ 25-second duration
✅ Auto-playing with progress bar
✅ Click to restart
✅ Bright, playful colors
✅ Professional transitions
✅ Emoji support 🎨

## Technical Details

- **No dependencies**: Pure HTML, CSS, and JavaScript
- **Browser support**: All modern browsers (Chrome, Firefox, Safari, Edge)
- **Mobile responsive**: Optimized for 1080x1920 Instagram format
- **Performance**: Smooth 60fps animations
- **File size**: ~10KB (single HTML file)

## Tips for Best Results

1. **Use a clean browser window** without toolbars for recording
2. **Zoom to 100%** for crisp rendering
3. **Wait 1-2 seconds** before starting the recording to ensure smooth start
4. **Use good lighting** if recording your screen with a camera
5. **Consider adding upbeat background music** in your video editor
6. **Test on mobile** before posting to Instagram

## Sharing on Instagram

1. Transfer the recorded video to your phone
2. Open Instagram
3. Tap "+" to create a new post
4. Select "Story" or "Reel"
5. Upload your video
6. Add music from Instagram's library (optional)
7. Post and tag #GIS #MappingTools #OpenSource

## Troubleshooting

**Animation not smooth?**
- Try using Chrome for best performance
- Close other browser tabs
- Restart your browser

**Colors look different after recording?**
- Check your screen color profile settings
- Try recording at 60fps if your tool supports it
- Use a professional screen recorder

**File size too large?**
- Compress the video using HandBrake or similar tools
- Record at 30fps instead of 60fps
- Use H.264 codec for better compression

## License

Feel free to use, modify, and share this animation!

## Credits

Designed for showcasing GIS tools and resources for the geospatial community.

---

**Made with ❤️ for the GIS community** 🗺️
