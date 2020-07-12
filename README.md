# Steps to deploy the app on github

### 1. Create new public repo in github

### 2. Go to package.json
```
1. Add "homepage": "https://hanskoh.github.io/react-todolist-app",
2. In "scripts" add "predeploy": "npm run build",
   In "scripts" add  "deploy": "gh-pages -d build"
```

### 3. link local project to created new public github repo
```
git remote add origin https://github.com/HansKoh/react-todolist-app.git
```

### 4. install gh-pages dependency
```
npm install --save gh-pages
```

### 5. build the project
```
npm run build
```

### 6. deploy the project
```
npm run deploy
```

### 7. Go to the homepage link
```
https://hanskoh.github.io/react-todolist-app
```