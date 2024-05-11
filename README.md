# Simple create-react-app Template

A very simple starter template for [create-react-app](https://create-react-app.dev).

```sh
npx create-react-app myapp --template @thomd/cra-template-simple
cd myapp
npm start
```

The template creates the following code structure

`src/index.js`:

```javascript
import React, { StrictMode } from 'react'
import { createRoot } from 'react-dom/client'
import App from './App'

createRoot(document.getElementById('root')).render(<StrictMode><App /></StrictMode>)
```

`src/App.jsx`:

```javascript
export default function App() {
  return (<>React</>)
}
```
