# Shalom Design System

A comprehensive Design System for Angular applications with Storybook integration.

## Overview

Shalom Design System provides a cohesive set of components, patterns, and tools to build consistent Angular applications while following design best practices.

## Features

- Pre-built Angular components with consistent styling
- Comprehensive design tokens and theme system
- Storybook integration for component documentation and visualization
- Accessibility compliance built-in
- Responsive design patterns

## Getting Started

### Usage

Import components into your Angular application:

```typescript
import { ButtonModule } from "shalom-design-system";

@NgModule({
  imports: [ButtonModule],
})
export class AppModule {}
```

### Development server

Run the development server:

```bash
ng serve
```

Navigate to `http://localhost:4200/` to view the application.

### Storybook

Launch Storybook to explore and interact with the design system components:

```bash
npm run storybook
```

Navigate to `http://localhost:6006/` to access Storybook.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
