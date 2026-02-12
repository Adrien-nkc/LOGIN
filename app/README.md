# How to install tailwind CSS in a vite + react project

`npm install tailwindcss @tailwindcss/vite`

# Configure the vite plugins inside `vite.config.ts`

```ts
import { defineConfig } from "vite";
import react from "@vitejs/plugin-react";
import tailwindcss from "@tailwindcss/vite";

// https://vite.dev/config/
export default defineConfig({
  plugins: [react(), tailwindcss()],
});
```

# Import tailwind to the index.css file

`@import "tailwindcss";`
