# Codelapse UI

Small, playful UI components from the [Codelapse](https://www.youtube.com/@codelapse) Shorts.
Each one is a single `index.html` file: plain HTML, CSS and JavaScript, no build step, no dependencies.
Open it in a browser, or copy the parts you need.

**Play online:** [Drive Baku](https://zulfuqarovelnar.github.io/codelapse-ui/drive-baku/) · [Night city](https://zulfuqarovelnar.github.io/codelapse-ui/drive-city/) · every component runs at `https://zulfuqarovelnar.github.io/codelapse-ui/<folder>/`

| Component | Folder |
|---|---|
| Book button that cuts itself ✂️ | [scissor-button](scissor-button) |
| Order button that brews itself ☕ | [coffee-order](coffee-order) |
| Snap button that prints a polaroid 📸 | [camera-flash](camera-flash) |
| Blow out the candle for dark mode 🕯️ | [candle-dark-mode](candle-dark-mode) |
| Like button that bursts into hearts ❤️ | [heart-burst](heart-burst) |
| A toast notification from a toaster 🍞 | [toaster-toast](toaster-toast) |
| Delete button that shreds the file 🗑️ | [shredder-delete](shredder-delete) |
| Deploy button that actually launches 🚀 | [rocket-deploy](rocket-deploy) |
| Upload button that floats away 🎈 | [balloon-upload](balloon-upload) |
| Subscribe button with a real mailbox 📬 | [mailbox-subscribe](mailbox-subscribe) |
| 5-star rating with a wanted level 🚨 | [wanted-stars](wanted-stars) |
| Mission-complete checkout 💰 | [mission-checkout](mission-checkout) |
| Car radio station switcher 📻 | [radio-dial](radio-dial) |
| Cheat code input 🎮 | [cheat-code](cheat-code) |
| Game-style phone that slides up, with a message notification 📱 | [phone-menu](phone-menu) |
| Scroll zoom reveal in pure CSS (the GTA 6 website effect) 🌴 | [scroll-zoom-reveal](scroll-zoom-reveal) |
| The same scroll zoom with GSAP + ScrollTrigger, for comparison | [scroll-zoom-reveal/gsap.html](scroll-zoom-reveal/gsap.html) |
| Headline that fills with colour as you scroll 🌅 | [scroll-text-fill](scroll-text-fill) |
| Character card that opens as you scroll 🏄 | [character-reveal](character-reveal) |
| Scroll to drive: a GPS route on a 3D map 🚗 | [scroll-map-drive](scroll-map-drive) |
| A drivable 3D night city: arrow keys, drifting, traffic, GPS (Three.js) 🌃 | [drive-city](drive-city) |
| Drive Baku at night: Neftchilar Avenue, Old City, Maiden Tower, Flame Towers, GPS route on a minimap, engine sounds (Three.js) 🇦🇿 | [drive-baku](drive-baku) |
| Character cards that morph into a page (View Transitions) ✨ | [view-transition-cards](view-transition-cards) |
| Apple-style 3D product scroll: the headphones turn, explode into labelled parts and come back together (Three.js) 🎧 | [scroll-3d-product](scroll-3d-product) |

The scroll effects use CSS scroll-driven animations (`animation-timeline`), supported in Chrome/Edge 115+, Safari 26+ and Firefox 159+.
`view-transition-cards` uses the View Transitions API (Chrome/Edge 111+, Safari 18+, Firefox 144+); elsewhere the card simply opens without the animation.
The photos in `character-reveal` and `view-transition-cards` are public domain (CC0), from Wikimedia Commons: [surfer](https://commons.wikimedia.org/wiki/File:The_Last_Ride_(Unsplash).jpg), [motel sign](https://commons.wikimedia.org/wiki/File:Ambassador_Motel.jpg), [lifeguard tower](https://commons.wikimedia.org/wiki/File:Lifeguarded_(Unsplash).jpg).

`drive-city`, `drive-baku` and `scroll-3d-product` load [Three.js](https://threejs.org) (MIT) from a CDN; everything else is in the one file. The Baku landmarks are simplified fan-made models.

MIT licensed. Use them in your own projects, paid or free.
