# Digital Clock - Multi-Timezone Display

A lightweight web app that shows the current time across multiple time zones in real time.

## Overview

This project is a simple frontend app built with HTML, CSS, and JavaScript. It uses the browser's `Intl` API to format times for different cities or time zones and refreshes every second.

## Features

- Multiple timezone support
- Live clock updates every second
- Responsive layout for desktop and mobile
- Clean, minimal interface
- No external dependencies required

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6+)
- `Intl.DateTimeFormat` API

## Project Structure

```text
digital-clock-timezones/
├── index.html
├── style.css
├── script.js
├── README.md
└── LICENSE
```

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/sikandarali64/digital-clock-timezones.git
cd digital-clock-timezones
```

2. Open the app in a browser:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## How It Works

The app uses JavaScript to:

- get the current timestamp
- format it using the selected timezone
- update the displayed clock continuously

This is handled with the browser's built-in time APIs, which makes the project fast and easy to run without any backend.

## Use Cases

- Tracking global meetings
- Comparing time across countries
- Learning timezone conversion in frontend development

## Notes

- Timezone names should follow IANA format, such as `America/New_York` and `Europe/London`.
- The app is intentionally simple and can be extended with favorites, analog clocks, or timezone search.

## License

This project is open source and available under the MIT License.

## Author

Sikandar Ali - https://github.com/sikandarali64
