<!--
    Documentation:

    This README provides comprehensive setup and usage instructions for the TicketByte project, built with Next.js and React. It covers environment setup, dependency installation, UI integration, component creation, utility organization, and development tips.
-->

# TicketByte

TicketByte is a modern web application built using Next.js and React, designed for efficient ticket management and UI customization.

## Getting Started

### 1. Project Initialization

Create a new Next.js project:

```bash
npx create-next-app@latest
```

### 2. Install Core Dependencies

Install Next.js, React, and React DOM (using legacy peer dependencies):

```bash
npm i next@rc react@rc react-dom@rc --legacy-peer-deps
```

### 3. UI Integration with shadcn

Visit the [shadcn UI website](https://ui.shadcn.com/) for documentation.

Initialize shadcn UI in your project:

```bash
npx shadcn@latest init
```

If you encounter dependency errors, manually install required packages:

```bash
npm install class-variance-authority lucide-react clsx tailwind-merge --legacy-peer-deps
```

### 4. Creating Custom Components

To manually create a component (e.g., Button), install Radix UI Slot:

```bash
npm install @radix-ui/react-slot --legacy-peer-deps
```

Create your component files in the appropriate directory (e.g., `components/Button.tsx`).

### 5. Organizing Utility Functions

Create a folder named `lib` in your project root, and add a file named `utils.ts` for shared utility functions.

### 6. TypeScript Server Restart

After installing dependencies and creating files, restart the TypeScript server in VSCode to ensure proper type checking.

## Development Tips

- Use modular components for maintainability.
- Refer to official documentation for Next.js, React, and shadcn UI for advanced usage.
- Keep utility functions organized in the `lib` directory.
- Regularly update dependencies for security and stability.

## Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [React Documentation](https://react.dev/)
- [shadcn UI Documentation](https://ui.shadcn.com/)

---

Feel free to customize and extend this project as needed for your ticket management requirements.