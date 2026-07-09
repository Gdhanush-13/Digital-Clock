# Digital Clock

A real-time digital clock built with vanilla HTML, CSS, and JavaScript. Displays the current time with a clean, minimal interface.

## Features

- Live time display — updates every second
- Shows hours, minutes, and seconds
- Zero-padded for consistent formatting
- No dependencies — pure HTML/CSS/JS

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | JavaScript (`Date`, `setInterval`) |

## Getting Started

```bash
git clone https://github.com/Gdhanush-13/Digital-Clock.git
cd Digital-Clock
```

Open `index.html` in any modern browser — no build step needed.

## Project Structure

```
Digital-Clock/
├── index.html   # Clock markup
├── style.css    # Clock styling
└── main.js      # Time logic
```

## How It Works

```js
setInterval(() => {
  const now = new Date();
  // extract hours, minutes, seconds and update the DOM
}, 1000);
```

The `Date` object provides the current time; `setInterval` refreshes the display every 1 000 ms.

## License

MIT — free to use and modify.