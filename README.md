# React boilerplate

#### React SPA setup without using create-react-app which comes with unnecessary dependencies.

## Setting up the project:
1. Clone the repository (note the project name):
```
git clone https://github.com/NivEz/react-boilerplate.git <PROJECT_NAME_HERE>
```
or without git history:
```
git clone --depth 1 https://github.com/NivEz/react-boilerplate.git <PROJECT_NAME_HERE>
```

To change the last commit after the clone you can use:
```
git commit --amend -m "YOUR UPDATED MESSAGE"
```

2. Install dependencies:
```
yarn
```

3. Running dev server with hot reload on port 5000:
```
yarn dev
```
You can specify port with `--port <PORT>` flag or modify it in the `webpack.config.js` under `devServer.port`.

4. Build:
```
yarn build
```


* Feel free to PR any configuration improvements.
