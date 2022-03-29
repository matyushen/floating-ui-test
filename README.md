# A reproduction repo for the issue with floating-ui

Run the build command

```bash
yarn build
```

And observe the error

```
Failed to compile.

./node_modules/@floating-ui/react-dom-interactions/dist/floating-ui.react-dom-interactions.esm.js
Attempted import error: 'useId' is not exported from 'react' (imported as 'React').

Import trace for requested module:
./Tooltip.tsx
./pages/index.tsx


> Build failed because of webpack errors
```
