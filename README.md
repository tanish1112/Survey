# Student Pulse

A multi-step survey interface prototype for exploring how students experience and manage exam stress.

- Prompts for personal context, a 1–10 exam stress rating and written responses about coping strategies.
- Supports forward and back navigation and a reset from the completion screen.
- The completion screen is a UI preview. Responses are neither saved nor transmitted.

## Technologies

HTML, CSS and vanilla JavaScript. Typography is loaded from Google Fonts when available.

## Run locally

Clone the repository and open `index.html` in a modern browser. To serve it over HTTP, run:

```sh
git clone https://github.com/tanish1112/Survey.git
cd Survey
python3 -m http.server 8000
```

Open [localhost:8000](http://localhost:8000). Python is only needed for the optional local server.
