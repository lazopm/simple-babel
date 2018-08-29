# Simple Babel

### Installation
- `npm install`

### Transpiling
`npm run transpile` will convert any scripts inside the `src` directory and output them to `dist`. It will also copy the babel polyfill script to that directory.

### Including the polyfill 
You must include `polyfill.min.js` before using any transpiled scripts.
```html
    <script src="polyfill.min.js"/>
```
