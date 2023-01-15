## 1. Start

1. Install needed dependencies

   ```bash
   npm install
   ```

2. Run webpack

   The `dev` command will start a dev server and watch for code changes in JS and SCSS files. Hot reloading is enabled, so
   that any change will be visible in your browser as you type.

   ```bash
   npm run dev
   ```

   For production usage, run the `build` command and everything you need gets packed together into the `public`
   directory. You can upload the content to any hosting provider, without further modifications.

   ```bash
   npm run build
   ```