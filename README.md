# React Lighter

React Lighter is a React component for highlighting text within its children. It's a modern, React-based version of the popular `mark.js` library, built with TypeScript and optimized for performance.

## Features

- Highlight text within a component's children
- Serialize and deserialize highlights
- Customizable highlight styles
- Support for multiple highlight groups
- Attach metadata to highlights
- Navigate through highlights
- Optimized for performance with React hooks
- Supports React 18 and concurrent features

## Installation

To install React Lighter, you can use npm or yarn:

```bash
npm install @hellskater/react-lighter
# or
yarn add @hellskater/react-lighter
```

## Usage

Here's a basic example of how to use React Lighter:

```jsx
import { Lighter } from "@hellskater/react-lighter";

function MyComponent() {
  return (
    <Lighter text="highlight">This is some text with a highlight.</Lighter>
  );
}
```

In this example, the word "highlight" in the children of the `Lighter` component will be highlighted.

## Contributing

Contributions to React Lighter are welcome! Please see our [contributing guide](https://github.com/hellskater/react-lighter/CONTRIBUTING.md) for more details.

## License

React Lighter is licensed under the MIT License. See [LICENSE](https://github.com/hellskater/react-lighter/LICENSE) for more details.
