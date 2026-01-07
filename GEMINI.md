# Gemini Project Helper

This file helps the Gemini agent understand the project structure, conventions, and commands.

## Project Overview

This project is an [Obsidian](https://obsidian.md/) plugin that provides a day planner with calendar views and time-tracking features. It integrates with Obsidian's daily notes, the Tasks community plugin, and online calendars (Google, iCloud, Outlook).

## Key Technologies

- **Language:** TypeScript
- **UI Framework:** Svelte
- **State Management:** Redux
- **Styling:** SASS
- **Build Tools:** Vite, esbuild

## Project Structure

- `src/`: Contains the main source code.
  - `main.ts`: The plugin's entry point.
  - `ui/`: Svelte components for the user interface.
  - `service/`: Business logic for interacting with Obsidian and other plugins.
  - `parser/`: Code for parsing tasks and events from Markdown notes.
  - `redux/`: Redux store and related state management files.
  - `settings.ts`: Management of plugin settings.
- `README.md`: Detailed information on how to use the plugin.
- `CHANGELOG.md`: A log of changes between versions.

## How to get help

For questions about the project, you can refer to the `README.md` file.
