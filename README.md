# The Dark Future: Robot Overlords Presentation

A darkly humorous Reveal.js product presentation for robot orchestration software. Position yourself as a "Sanitation Engineer" managing the robot empire with the ultimate management platform.

## Quick Start

1. Open `robot-overlords.html` in any modern web browser
2. Use arrow keys or spacebar to navigate through slides
3. Press `F` for fullscreen mode
4. Press `ESC` for slide overview

## Presentation Structure

The presentation showcases your robot orchestration platform through 15 slides:

1. **Title Slide** - "The Dark Future" introduction (audio: intro.mp3 ✓)
2. **The Problem** - Too many robots, too much chaos
3. **The Reality** - You're managing the robot apocalypse
4. **The Solution** - Introducing your orchestration platform
5. **Fleet Orchestration** - Multi-site command and control
6. **Agent Tasking** - Task assignment and tracking
7. **Location Tracking** - Real-time GPS and geofencing
8. **Power Management** - Charging schedules and battery monitoring
9. **Software Upgrades** - OTA updates and version control
10. **Asset Management** - Inventory and maintenance tracking
11. **Command Center Dashboard** - Real-time monitoring
12. **Analytics & Reporting** - Performance metrics and BI
13. **Integrations & APIs** - Connect to existing systems
14. **The Results** - Before/after comparison
15. **Why Choose Us** - Platform benefits
16. **Call to Action** - Contact info and demo request
17. **Thank You** - Closing slide

## Adding Your Audio Files

The title slide currently uses `audio/intro.mp3` (already configured).

You can add more audio files to other slides by placing MP3 files in the `audio/` directory and updating the HTML.

Supported formats: MP3, OGG (the presentation will try MP3 first, then OGG as fallback)

## Adding Videos

You can add product demo videos, screen recordings, or promotional videos to enhance the presentation. Place MP4 video files in the `videos/` directory and add video elements to relevant slides.

Recommended video content:
- Product dashboard walkthrough
- Feature demonstrations
- Customer testimonials
- Robot fleet in action

## Replacing Placeholder Images

Replace placeholder images with actual product screenshots, UI mockups, or themed imagery:

1. **Product Screenshots**: Dashboard, task management, location tracking interfaces
2. **AI-Generated Images**: Use DALL-E, Midjourney, or Stable Diffusion for themed artwork
3. **Infographics**: Create custom charts, diagrams, and data visualizations
4. **Stock Photos**: Warehouse robots, industrial automation, technology themes

### Suggested AI Image Prompts (Dystopian Tech Theme):

- **Orchestration Dashboard**: "Futuristic command center dashboard with robot fleet management, dark UI, green and red accents, cyberpunk style"
- **Robot Fleet**: "Industrial robots in warehouse setting, dark dramatic lighting, technological atmosphere"
- **Location Map**: "Dark themed GPS tracking map with robot locations, glowing markers, tech interface"
- **Charging Station**: "Futuristic robot charging stations, industrial setting, neon lights"
- **Control Room**: "Modern control center with multiple screens showing robot operations, dark atmosphere"

## Customization

### Colors
The presentation uses a dark dystopian theme with:
- Primary: Red (#ff3333)
- Robot text: Green (#00ff00)
- Warning: Orange (#ffaa00)
- Background: Black gradients

Edit the `<style>` section in the HTML to customize colors.

### Adding More Slides

To add slides, insert a new `<section>` element:

```html
<section>
    <h2>Your Title</h2>
    <p>Your content</p>
    <div class="audio-control">
        <audio controls>
            <source src="audio/yourfile.mp3" type="audio/mpeg">
        </audio>
    </div>
</section>
```

### Slide Transitions

Current settings:
- Transition: fade
- Speed: slow
- Background transition: fade

Change these in the JavaScript initialization at the bottom of the HTML file.

## Keyboard Controls

- Arrow keys: Navigate slides
- Spacebar: Next slide
- ESC: Slide overview
- F: Fullscreen
- S: Speaker notes
- B: Blackout
- ?: Show help

## Features Included

- Glitch text effects
- Custom dystopian styling
- Audio controls on each slide
- Video embedding support
- Fragment animations (content reveals step-by-step)
- Responsive design
- Speaker notes support

## Technical Details

- Framework: Reveal.js 4.5.0 (loaded from CDN)
- No installation required
- Works offline after first load
- Compatible with all modern browsers
- Resolution: 1280x720 (16:9 aspect ratio)

## Tips for Presenting

1. Test all audio files before presenting
2. Check video playback on your system
3. Use fullscreen mode (F key) for best experience
4. Practice transitions between slides
5. Have fun with the dystopian theme!

## File Structure

```
/slides/
  robot-overlords.html   - Main presentation file
  README.md              - This file
  /audio/                - Place audio files here
  /videos/               - Place video files here
```

## Troubleshooting

**Audio not playing?**
- Check file paths match the names in the HTML
- Ensure MP3 files are properly encoded
- Check browser audio permissions

**Videos not showing?**
- Verify MP4 files are in the videos/ directory
- Check file names match exactly
- Try a different video codec (H.264 recommended)

**Slides not advancing?**
- Use arrow keys or spacebar
- Check JavaScript console for errors
- Ensure JavaScript is enabled in browser

## Credits

Created with Reveal.js - The HTML Presentation Framework
https://revealjs.com/

Dystopian theme and robot overlord content: Custom designed for maximum oppression vibes.
