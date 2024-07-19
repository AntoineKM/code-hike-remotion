## !!steps Before

!duration 180

```jsx ! next.config.mjs
// @ts-check

/**
 * @type {import('next').NextConfig}
 */
const nextConfig = {
  /* config options here */
}

export default nextConfig
```

## !!steps After

!duration 420

```tsx ! next.config.ts
import { defineConfig } from 'next/config'

const nextConfig = defineConfig({
  /* config options here */
})

export default nextConfig
```
