# joseph-theme

Custom Ghost theme for josephvoelbel.com. Hyper-minimal, typography-first.

## Features
- Minimal single-column layout
- Ghost Pro compatible (v5+)
- Audio player styling (slim, branded)
- Page template with proper `{{#page}}` context
- Code injection compatible

## Deploy
Upload `joseph-theme.zip` via Ghost Admin → Settings → Change Theme → Upload Theme.

## Code Injection
The live site relies on code injection (Ghost Admin → Settings → Code injection) for the search widget, the "Ask This Resume" widget (/ai-resume), inline subscribe box, nav, and structured data. That code is NOT part of the theme package — Ghost stores it separately in the database. A backup of the live head + foot injection is kept in `code-injection/head.html` and `code-injection/foot.html` in this repo. Keep them in sync whenever the live injection changes.
