# 📊 AI-Driven Dev {Benchmark}

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Contributors](https://img.shields.io/badge/contributors-welcome-orange)
[![Discord](https://img.shields.io/discord/1173363373115723796?color=7289da&label=discord&logo=discord&logoColor=white)](https://bit.ly/alexsoyes-discord)

**A comprehensive benchmark suite for comparing Large Language Models (LLMs) performance and capabilities.**

## 📑 Table of Contents

- [📑 Table of Contents](#-table-of-contents)
- [📊 Benchmark Results](#-benchmark-results)
- [🔍 Test Cases](#-test-cases)
  - [Code Generation "Tic-Tac-Toe Game"](#code-generation-tic-tac-toe-game)

## 📊 Benchmark Results

| Tool | Test Date | URL | Code Generation | Score |
|-------|-----------|-----|-----------------|-------|
<!-- | Todo | 2024-03-20 | []() | ⭐⭐⭐⭐⭐ | 4.5/5 | -->

## 🔍 Test Cases

- [x] Code Generation
- [ ] Bug Fixing
- [ ] Code Review
- [ ] Documentation Writing
- [ ] Problem-Solving
- [ ] Domain-Specific Tasks

### Code Generation "Tic-Tac-Toe Game"

````markdown
# Prompt: Create a Tic-Tac-Toe Game in React with TypeScript using Clean Architecture, MobX, and Comprehensive Testing

## Requirements

- **Framework**: Use React with TypeScript.
- **State Management**: Use **MobX** for managing application state.
- **Architecture**: Implement a **Clean Architecture** structure with clear separation of concerns:
  - **Domain Layer**: Handle game logic and rules.
  - **Application Layer**: Manage state with a MobX store.
  - **Presentation Layer**: Render UI with React components.

## Functional Details

- Implement a fully functional **Tic-Tac-Toe** game with the following features:
  - A 3x3 grid where players alternately mark "X" or "O".
  - Indicate the active player.
  - Detect win conditions (three in a row: horizontal, vertical, or diagonal).
  - Detect a draw when no moves remain without a winner.
  - Prevent moves in already occupied cells.
  - Include a "Reset" button to restart the game.

## Testing Requirements

- **Unit Tests**: Cover:
  - Domain logic (e.g., win and draw detection).
  - Store operations (e.g., state changes for moves, resets).
- **Integration Tests**: Ensure seamless interaction between the store and UI.
- **End-to-End Tests**: Verify game behavior in a browser environment, including:
  - Correct rendering of the grid and game state.
  - User interaction flows (e.g., making moves, resetting the game).

## File Structure

- Follow a **Clean Architecture** structure:
  - `domain/`: Define models and pure logic.
  - `application/`: Implement MobX stores and use cases.
  - `presentation/`: Build React components and pages.
  - `tests/`: Organize unit, integration, and end-to-end tests.

## Additional Requirements

- Ensure type safety with TypeScript.
- Use reusable and testable helper functions for all domain logic.
- Structure the code and tests for scalability and maintainability.

## Bonus (Optional)

- Add visual feedback for the winning sequence (highlight the row, column, or diagonal).
- Implement undo functionality.
- Create a testing report with coverage metrics.

````
