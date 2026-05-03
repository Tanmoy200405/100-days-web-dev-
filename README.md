# 100 Days Web Dev

## Day 1: Background Video Hero Section



### Features
- Full-screen responsive background video (autoplay, loop, muted).
- Dark gradient overlay.
- Centered animated heading \"Journey\" (hover: outline effect).
- \"Explore\" CTA button (hover: white bg).
- Mobile-friendly video scaling via CSS media queries.

### Key Code
**HTML (Video Setup):**
```html
<video autoplay loop muted plays-inline class=\"back-video\">
  <source src=\"assets/video.mp4\" />
</video>
```

**CSS (Background Video):**
```css
.back-video {
  position: absolute;
  right: 0;
  bottom: 0;
  z-index: -1;
}
@media (min-aspect-ratio: 16/9) {
  .back-video { width: 100%; height: auto; }
}
@media (max-aspect-ratio: 16/9) {
  .back-video { width: auto; height: 100%; }
}
```

### How to Run
1. Open `day-1/index.html` in browser.
2. Replace `assets/video.mp4` with your video.

**Progress:** Day 1/100 ✅

