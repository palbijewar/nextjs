## Next.js

Next.js is a powerful React framework that extends React's capabilities to build modern, production-ready web applications. It provides essential features such as:

- **Routing**: Built-in file-based routing for easier navigation.
- **Optimized Rendering**: Support for Server-Side Rendering (SSR), Static Site Generation (SSG), and Client-Side Rendering (CSR) to enhance performance.
- **Data Fetching**: Seamless integration for fetching data during build time, on the server, or in the browser.
- **Bundling and Compiling**: Automatic optimization of JavaScript and CSS for faster load times.
- **Additional Features**: API routes, image optimization, TypeScript support, and more.

Next.js simplifies the development process, making it easier to deliver fast and scalable web applications.

## React Server Components

In Next.js, all components are **server components** by default. This allows for optimized rendering and improved performance by running on the server.

### Creating a Client Component

To define a **client component**, include `"use client"` at the top of the component file. For example:

```javascript
"use client";

import React from "react";

export default function MyClientComponent() {
    return <div>This is a client component.</div>;
}
```

### Key Differences:
- **Server Components**: Rendered on the server and sent to the client as static HTML, reducing JavaScript sent to the browser.
- **Client Components**: Rendered on the client and can use state, effects, or browser-specific APIs.

Understanding when to use server or client components helps in optimizing your Next.js applications. 
