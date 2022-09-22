    Youtube [Tailwind CSS Tutorial](https://www.youtube.com/playlist?list=PL4cUxeGkcC9gpXORlEHjc5bgnIi5HEGhw)

2. Setup.

- The istructors script for package.json
  - "build-css": "tailwindcss build src/styles.css -o public/styles.css"

4. Taiwind Config

- We recreated the `tailwind.config.js` with `npx tailwindcss init --full` by adding `--full`. Now in the config file we can add new values of modify the existing ones. But, then we need to re-process it `npm run build-css`. It is not recomented though. We could also make a blank config file and extend the default rules. So to create a custom color, rename the config file, run `npx tailwindscss init ` and add the new color in the `extend` property. Then run `npm run build-css`

- 6. Custom fonts
