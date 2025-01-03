# react-tna

React hook, libs, utils, react UI framework, library, ready to use, written in TypeScript.

## 💫 Introduction

This is a React hooks library, written in TypeScript and react-tna. It provides a set of hooks that enables you to build your React applications faster. The hooks are built upon the principles of DRY (Don't Repeat Yourself). There are hooks for most common use cases you might need.

The library is designed to be as minimal as possible. It is fully tree-shakable (using the ESM version), meaning that you only import the hooks you need, and the rest will be removed from your bundle making the cost of using this library negligible. Most hooks are extensively tested and are being used in production environments.

## 🚀 Installation

To install the library, run:

```bash
npm install react-tna
```

or

```bash
yarn add react-tna
```

## 📖 Usage

Here's an example of how to use one of the hooks:

```tsx
import { useLocalStorage } from 'react-tna'

function Component() {
  const [value, setValue] = useLocalStorage('my-localStorage-key', 0)

  return (
    <div>
      <p>Stored value: {value}</p>
      <button onClick={() => setValue(value + 1)}>Increment</button>
    </div>
  )
}
```

## 📚 Features

- **react-tna**: Minimal setup and easy integration.
- **TypeScript Support**: Fully typed for a great developer experience.
- **Tree-Shakable**: Import only what you need.
- **Production-Ready**: Extensively tested and used in production.

## 🤝 Contributing

Contributions are welcome! If you have ideas, suggestions, or find bugs, feel free to open an issue or submit a pull request.

### Running Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/react-tna.git
   ```

2. Install dependencies:

   ```bash
   cd react-tna
   pnpm install
   ```

3. Start the development server:

   ```bash
   pnpm dev
   ```

## 📄 License

This project is licensed under the MIT License. See the LICENSE file for details.
