# Election Guide Assistant

> Built on **Google Antigravity** for **Virtual Prompt Wars** by **Google for Developers** and **Hack2Skill**...  
> Live demo: https://clashlex.github.io/Election-Guide/

## Project Overview

**Election Guide Assistant** is a non-partisan civic education web app that explains the election process in a simple, interactive, and accessible way. It is designed to help first-time voters, students, and general users understand how elections work from start to finish.

The project is delivered as a **single-file HTML application** (`ElectionGuide.html`) with no backend, no build pipeline, and no dependency installation. It runs directly in the browser.

## Why this project exists

Many people know they are allowed to vote, but still feel uncertain about the process. Common questions include:

- How do I register?
- What ID do I need?
- How does voting day work?
- What happens after voting?
- How can I track my readiness?

This app answers those questions in one place with a clear structure and a polished interface.

## Key Features

### 1. Hero section
A clean landing area introduces the app with a strong title, supporting text, and quick actions to begin exploring the timeline or eligibility checker.

### 2. Election timeline
A 6-stage interactive timeline explains the election journey in order:

1. Voter Registration
2. Candidate Nomination
3. Campaigning Period
4. Voting Day
5. Vote Counting
6. Result Announcement

Each stage includes:
- A short explanation of what the stage covers
- A practical action prompt that tells the user what to do next

The timeline is responsive and works well on both desktop and mobile devices.

### 3. Eligibility checker
A private 4-step question flow helps the user assess whether they are ready to vote.

It checks:
- Age
- Citizenship
- Residency
- Registration status

The logic is interactive and gives context-sensitive outcomes such as:
- Ready to vote
- Eligible but not registered
- Not yet eligible
- Check registration status

### 4. FAQ assistant
The built-in FAQ section gives quick answers to common voting questions, including:

- Registration
- Voting day
- ID requirements
- Vote counting
- Ballot mistakes
- Mail-in voting
- Poll observers
- Missed deadlines

It also includes a search input so users can type a question and get a relevant answer quickly.

### 5. Progress tracker
A 6-item checklist helps users stay organized before election day. Progress is saved in the browser using `localStorage`, so it remains available after refresh.

### 6. Dark mode
The app includes a light/dark theme toggle. It also respects the user's system preference on first load and remembers the selected theme.

### 7. Fully responsive layout
The layout adapts across screen sizes:
- Desktop sidebar navigation
- Mobile bottom navigation
- Touch-friendly controls
- Accessible spacing and focus states

## Tech Stack

| Layer | Technology |
|---|---|
| Structure | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript |
| Icons | Font Awesome |
| Typography | Google Fonts |
| State Persistence | Browser `localStorage` |
| Deployment | Static hosting |

## Project Structure

```text
ElectionGuide.html   # Main application file
README.md            # Project documentation
```

## How to Run

### Open locally
Open `ElectionGuide.html` in any modern browser.

### Run a simple local server
```bash
python3 -m http.server 8080
```

Then open:

```text
http://localhost:8080
```

## Deployment

Since this is a static front-end project, it can be deployed easily to:

- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

### Live Demo
https://clashlex.github.io/Election-Guide/

## Accessibility Notes

The app is built with usability in mind:
- Semantic HTML sections
- Keyboard-accessible controls
- Visible focus indicators
- Clear labels and button states
- Mobile-friendly tap targets

## Submission Details

This project was created for **Virtual Prompt Wars**, hosted by **Google for Developers** and **Hack2Skill**, and built using **Google Antigravity**.

## Highlights

- Single-file implementation
- No installation required
- Offline-friendly structure
- Educational and non-partisan content
- Responsive and polished UI
- Persistent user progress
- Clear voting guidance

## Author

**Ansil Muhammed N S**  
GitHub: [@ClashLex](https://github.com/ClashLex)

## License

Open source under the MIT License.
