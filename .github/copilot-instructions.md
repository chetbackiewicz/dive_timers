- This application to a be a cross platform application React Native application with Expo
- The application should be made to run on a smartphone
- The UI should gluestack and nativewindUI
- The programming language should be in Typescript
- When developing in Typescript, you should ideally:
	•	Use strong typing everywhere
	•	Define interfaces and types for function inputs, outputs, components, and API responses.
	•	Avoid any unless absolutely necessary.
	•	Organize code with a modular folder structure
	•	Group files by feature/domain (e.g., models/, services/, controllers/, types/, etc.).
	•	Use index.ts to re-export modules cleanly.
	•	Use enums and literal types for clear value constraints
	•	Replace magic strings/numbers with enums or string union types.
	•	Define API request/response types
	•	Use interfaces or OpenAPI-generated types to ensure type safety with backends.
	•	Use Axios with typed request/response models.
	•	Leverage generics for reusability
	•	Use generics in utility functions, services, or data models to keep code DRY and flexible.
	•	Configure TypeScript for strictness
    •	Enable "strict": true in tsconfig.json.
	•	Use ESLint + Prettier for consistent code
	•	Add @typescript-eslint plugin to catch TypeScript-specific issues.
	•	Format code automatically with Prettier for readability.
	•	Write type-safe tests
	•	Use testing frameworks like Jest or Vitest with TypeScript support.
	•	Create typed mocks and ensure inputs/outputs are covered.