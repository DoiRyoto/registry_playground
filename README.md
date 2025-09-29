# Custom UI Registry

A custom UI component registry compatible with v0 and shadcn/ui, following the shadcn/ui registry pattern.

## Features

- 🎨 **shadcn/ui Compatible**: Components follow the same patterns and structure as shadcn/ui
- 🔧 **v0 Ready**: Fully compatible with v0 for seamless integration
- 📦 **Registry Format**: Follows the official registry.json specification
- 🎯 **TypeScript**: Full TypeScript support with proper type definitions
- 🌙 **Dark Mode**: Built-in dark mode support with CSS variables
- 🎪 **Tailwind CSS**: Styled with Tailwind CSS and custom CSS variables

## Components

- **Button**: Customizable button component with multiple variants and sizes
- **Card**: Card components with header, content, and footer sections
- **Input**: Styled input component
- **Badge**: Badge component with different variants
- **useLocalStorage**: React hook for localStorage management

## Installation

```bash
npm install custom-ui-registry
```

## Usage

```tsx
import { Button, Card, CardHeader, CardTitle, CardContent } from 'custom-ui-registry'

function App() {
  return (
    <Card>
      <CardHeader>
        <CardTitle>Hello World</CardTitle>
      </CardHeader>
      <CardContent>
        <Button>Click me</Button>
      </CardContent>
    </Card>
  )
}
```

## Registry Configuration

This package includes a `registry.json` file that defines all available components, their dependencies, and metadata. This allows the components to be used with tools that support the shadcn/ui registry format.

## Development

```bash
# Install dependencies
npm install

# Build the library
npm run build

# Run type checking
npm run type-check

# Format code
npm run format
```

## License

MIT