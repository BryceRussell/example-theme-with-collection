# Example of Theme with Content Collections

### How

1. Theme provides a dynamic route `/[...slug].astro` that creates routes using the `blog` Content Collection
2. User adds content to Collection (in this case `/playground/src/content/blog` for testing) and the markdown files are turned into pages

- [Dynamic `[...slug].astro` route](https://github.com/BryceRussell/example-theme-with-collection/blob/main/package/src/pages/%5B...slug%5D.astro)
- [User defined content/pages using markdown](https://github.com/BryceRussell/example-theme-with-collection/tree/main/playground/src/content/blog)
