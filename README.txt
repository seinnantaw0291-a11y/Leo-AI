LEO AI — Free Starter Web App

Files:
- index.html: the app
- manifest.webmanifest: installable web app metadata
- sw.js: basic offline caching

Important:
This is a starter prototype, not a full connected AI yet.
The first version includes:
- ON/OFF session switch (stays ON until user turns it OFF)
- text chat with basic built-in commands
- browser speech input where supported
- spoken replies where supported
- links to Google, YouTube, Canva, CapCut and ChatGPT

Limitations:
- Advanced AI answers need a separate AI service/API. Free tiers can change and may have usage limits.
- Wake word listening while the app is closed/backgrounded is not supported by this web prototype.
- Opening phone apps depends on Android/browser support and installed apps.
- Image generation and video editing are opened through external services; the app does not yet edit media internally.

To publish free:
Upload these files to a public GitHub repository and enable GitHub Pages.
Use HTTPS so microphone permissions can work.
