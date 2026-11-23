# digital-clock-app

A digital clock (stopwatch style) built with React. Counts up in
HH:MM:SS format and can be controlled with Start, Pause, and Stop
buttons.

## Concepts demonstrated

- useState — tracks the elapsed seconds and whether the clock is running.
- useEffect + setInterval — updates the count every second while running.
- Props — App.jsx passes `time` and `isRunning` down to the ClockDisplay
  component, which just displays what it's given.

## How to run

1. Unzip this folder.
2. Open it in VS Code: `code .`
3. Open a terminal (Terminal -> New Terminal). If it opens as
   PowerShell, type `cmd` and press Enter to switch to Command Prompt.
4. Install dependencies:
   ```
   npm install
   ```
5. Start the dev server:
   ```
   npm run dev
   ```
6. Open the printed link (usually http://localhost:5173) in your browser.

## What's inside

- `src/main.jsx` — entry point, mounts <App /> into index.html's #root div.
- `src/App.jsx` — holds the timer state and Start/Pause/Stop logic.
- `src/Components/ClockDisplay.jsx` — receives the current time as a
  prop and displays it.
