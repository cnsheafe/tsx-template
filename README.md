TSX-Template
=

Install
-

```bash
npm install
npm install -g webpack
npm install -g webpack-dev-server
```

Usage
-

Set up directories for where the app files will live. The following directory structure is a good example. 

```bash
app/
├── dist
│   ├── bundle.js
│   ├── bundle.js.map
│   └── index.html
└── src
    ├── actions.ts
    ├── components
    │   ├── App.tsx
    │   └── Signup.tsx
    ├── index.tsx
    ├── reducer.ts
    └── store.ts
```

By default, the script will look for ```app/src/index.tsx``` . Refer to [config-tsx](https://github.com/cnsheafe/config-tsx) for custom file paths.

After the setup run either ```webpack``` or ```npm start```.
```bash
\\ Build-only
 webpack

\\ Build and run developer server
npm start
```