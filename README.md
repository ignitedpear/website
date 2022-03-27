Refer : https://reactjs.org/docs/add-react-to-a-website.html


Add JSX to project:
Step 1: Run npm init -y (if it fails, here’s a fix)
Step 2: Run npm install babel-cli@6 babel-preset-react-app@3


Run JSX Preprocessor:
npx babel --watch src --out-dir . --presets react-app/prod

Another command:
npx babel --watch src --out-file bundle.js --presets react-app/prod
Refer https://stackoverflow.com/questions/39471896/how-to-compile-all-included-files-into-one-using-babel
