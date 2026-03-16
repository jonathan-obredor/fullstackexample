# Changelog

## 2026-03-16 22:55 (Part 1 - Refactor: project reorganization)

- Moved unicafe source files from `part1/src/` to a new `part1/unicafe/` Vite React app. Removed old `part1/src/` and all loose root-level files (`index.html`, `package.json`, `node_modules/`, etc.).
- Created [part1/courseinfo](part1/courseinfo) as a new Vite React app placeholder for upcoming courseinfo exercises.
- `part1/` now contains only three independent apps: `unicafe/`, `anecdotes/`, `courseinfo/`.

## 2026-03-16 22:39 (Part 1 - Exercise 1.12)

- Created [part1/anecdotes](part1/anecdotes) as a separate Vite React app for the anecdotes exercises. Installed vite 8.0.0, react 19.2.4, and react-dom 19.2.4.
- Updated [part1/anecdotes/src/App.jsx](part1/anecdotes/src/App.jsx) and [part1/anecdotes/src/main.jsx](part1/anecdotes/src/main.jsx) for exercise 1.12. Added random anecdote selection with a `next anecdote` button and removed the starter CSS and asset files.

## 2026-03-16 22:22 (Part 1 - Exercise 1.11)

- Updated [part1/src/App.jsx](part1/src/App.jsx) for exercise 1.11. Changed `StatisticLine` and `Statistics` to render the `unicafe` statistics inside an HTML table.

## 2026-03-16 22:19 (Part 1 - Exercise 1.10)

- Updated [part1/src/App.jsx](part1/src/App.jsx) for exercise 1.10. Extracted `Button` for feedback actions and `StatisticLine` for rendering each statistics row in the `unicafe` app.

## 2026-03-16 22:18 (Part 1 - Exercise 1.9)

- Updated [part1/src/App.jsx](part1/src/App.jsx) for exercise 1.9. Added conditional rendering so `Statistics` shows `No feedback given` until at least one feedback item exists.

## 2026-03-16 22:16 (Part 1 - Exercise 1.8)

- Updated [part1/src/App.jsx](part1/src/App.jsx) for exercise 1.8. Extracted the feedback statistics into a separate `Statistics` component while keeping all `unicafe` state in `App`.

## 2026-03-16 22:13 (Part 1 - Exercise 1.7)

- Updated [part1/src/App.jsx](part1/src/App.jsx) for exercise 1.7. Added `all`, `average`, and `positive` statistics to the `unicafe` app using values derived from `good`, `neutral`, and `bad`.

## 2026-03-16 22:10 (Part 1 - Exercise 1.6)

- Updated [part1/src/App.jsx](part1/src/App.jsx) for exercise 1.6. Replaced the course app with the first `unicafe` version using `useState` for `good`, `neutral`, and `bad`, plus buttons and basic statistics output.

## 2026-03-16 21:37 (Part 1 - Exercise 1.5)

- Updated [part1/src/App.jsx](part1/src/App.jsx) for exercise 1.5. Replaced the separate `course` name and `parts` array with a single `course` object and wired components to use `course.name` and `course.parts`.

## 2026-03-16 21:34 (Part 1 - Exercise 1.4)

- Updated [part1/src/App.jsx](part1/src/App.jsx) for exercise 1.4. Moved the three part objects into a `parts` array and passed that array to `Content` and `Total`.

## 2026-03-16 00:00 (Part 1 - Exercise 1.3)

- Updated [part1/src/App.jsx](part1/src/App.jsx) for exercise 1.3. Replaced primitive part variables with part objects and adapted `Part`, `Content`, and `Total` to use object props.

## 2026-03-16 (Part 1 - Exercise 1.2)

- Added `Part` component to `part1/src/App.jsx`. Refactored `Content` to render three `Part` sub-components instead of inline paragraphs.

## 2026-03-16 (Part 1 - Exercise 1.1)

- Implemented exercise 1.1 (Course Information). Refactored `part1/src/App.jsx` into three components: `Header`, `Content`, and `Total`. Data stays in `App` and is passed down via props.

## 2026-03-12 22:35

- Installed nvm v0.40.1 and Node.js v22.22.1 LTS (upgraded from v18). Modified `~/.bashrc`.
- Created Vite + React project in `part1/` using `npm create vite@latest` (vite v8.0.0, react v19.x).
- Added Part 0 exercise diagrams: `part0/0.4.md`, `part0/0.5.md`, `part0/0.6.md`.
