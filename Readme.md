Lerna multirepo demo

To run the script:
```
npm i
npx lerna bootstrap
npm start
```

What happened? the carweb-app package has dependencies to the packages "a" and "b". lerna symlinked these deps into node_modules of the carweb-app package.

