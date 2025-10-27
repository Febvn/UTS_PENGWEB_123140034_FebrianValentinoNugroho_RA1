File: package.json

```json
{
  "name": "news-portal",
  "private": true,
  "version": "0.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "lint": "eslint . --ext js,jsx --report-unused-disable-directives --max-warnings 0",
    "preview": "vite preview"
  },
  "dependencies": {
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "styled-components": "^5.3.11"
  },
  "devDependencies": {
    "@types/react": "^18.2.15",
    "@types/react-dom": "^18.2.7",
    "@vitejs/plugin-react": "^4.0.3",
    "eslint": "^8.45.0",
    "eslint-plugin-react": "^7.32.2",
    "eslint-plugin-react-hooks": "^4.6.0",
    "eslint-plugin-react-refresh": "^0.4.3",
    "vite": "^4.4.5"
  }
}
```

Penjelasan:
- `scripts`: perintah convenience untuk development (`dev`), build (`build`), linting (`lint`) dan preview.
- `dependencies`: runtime dependencies (React, styled-components).
- `devDependencies`: tooling untuk development (Vite, ESLint, plugin react).
- Catatan: Versi paket adalah range (caret ^) — untuk produksi Anda bisa mempertimbangkan lockfile atau pin versi.
