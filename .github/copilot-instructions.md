# Application Development Guidelines

## Overview
- This application is a cross-platform React Native application built with Expo.
- The application is designed to run on smartphones.
- The UI framework should use **Gluestack** and **NativeWindUI**.
- The programming language for the application is **TypeScript**.

## TypeScript Development Best Practices
- When developing in TypeScript, adhere to the following guidelines:

### Strong Typing
- Use strong typing everywhere.
- Define interfaces and types for:
    - Function inputs and outputs.
    - Components.
    - API responses.
- Avoid using `any` unless absolutely necessary.

### Code Organization
- Organize code with a modular folder structure.
- Group files by feature or domain (e.g., `models/`, `services/`, `controllers/`, `types/`, etc.).
- Use `index.ts` files to re-export modules cleanly.

### Value Constraints
- Use enums and literal types for clear value constraints.
- Replace magic strings/numbers with enums or string union types.

### API Integration
- Define API request/response types.
- Use interfaces or OpenAPI-generated types to ensure type safety with backends.
- Use **Axios** with typed request/response models.

### Reusability
- Leverage generics for reusability:
    - Use generics in utility functions, services, or data models to keep code DRY and flexible.

### TypeScript Configuration
- Configure TypeScript for strictness:
    - Enable `"strict": true` in `tsconfig.json`.

### Code Quality
- Use **ESLint** and **Prettier** for consistent code:
    - Add the `@typescript-eslint` plugin to catch TypeScript-specific issues.
    - Format code automatically with Prettier for readability.

### Testing
- Write type-safe tests:
    - Use testing frameworks like **Jest** or **Vitest** with TypeScript support.
    - Create typed mocks and ensure inputs/outputs are covered.
- Ensure comprehensive test coverage.
