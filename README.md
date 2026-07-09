# Digital Clock

A real-time digital clock built with vanilla HTML, CSS, and JavaScript. Displays the current time in a clean, minimal interface â€” no libraries, no dependencies.

## Features

- Live time display updating every second
- Shows hours, minutes, and seconds with zero-padding
- Lightweight â€” pure HTML / CSS / JavaScript
- Works in any modern browser without a build step

## Tech Stack

| Layer | Technology |
|-------|------------|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | JavaScript (`Date`, `setInterval`) |

## Getting Started

`ash
git clone https://github.com/Gdhanush-13/Digital-Clock.git
cd Digital-Clock
`

Open **index.html** directly in your browser â€” no server needed.

## Project Structure

`
Digital-Clock/
â”œâ”€â”€ index.html   # Clock markup
â”œâ”€â”€ style.css    # Clock styling
â””â”€â”€ main.js      # Time logic (Date + setInterval)
`

## How It Works

Every 1 000 ms, JavaScript reads the current time from `new Date()`, extracts hours/minutes/seconds, pads them to two digits, and writes them into the DOM.

## License

MIT â€” free to use and modify.