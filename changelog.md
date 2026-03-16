# Changelog

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
