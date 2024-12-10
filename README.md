# Ken MCP Test

A TypeScript project exploring the Model-Controller-Presenter (MCP) architectural pattern, which offers a modern take on the traditional MVC pattern while providing better separation of concerns and testability.

## About MCP Pattern

The Model-Controller-Presenter (MCP) pattern is an architectural pattern that builds upon the concepts of MVC but addresses some of its limitations. Think of it as a restaurant where:

- **Model** (The Kitchen): Handles all the business logic and data, just like a kitchen prepares the food
- **Controller** (The Waiter): Manages user input and orchestrates the flow between Model and Presenter, like a waiter taking orders and delivering food
- **Presenter** (The Plating Chef): Formats the data for display and handles view logic, similar to how a plating chef makes the food presentable

### Key Benefits

- Clear separation of concerns
- Enhanced testability through dependency injection
- Better maintainability with isolated components
- Reduced coupling between UI and business logic
- Improved code reusability

## Project Structure

```
src/
├── models/       # Business logic and data structures
├── controllers/  # Input handling and flow control
├── presenters/   # View logic and data formatting
├── views/        # UI components (interfaces only)
└── types/        # TypeScript type definitions
```

## Getting Started

1. Clone this repository
2. Install dependencies: `npm install`
3. Run tests: `npm test`
4. Start development server: `npm start`

## Technologies

- TypeScript
- Jest for testing
- ESLint for code quality
- Prettier for code formatting

## Contributing

This is a test project for exploring the MCP pattern. Feel free to experiment and submit PRs for improvements or interesting implementations.

## License

MIT