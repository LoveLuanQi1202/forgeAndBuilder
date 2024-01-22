# forgeAndBuilder
compare electron forge and electron builder

1. yarn
2. yarn build
3. open dist/test/mac/eva-test
4. run "console.log(performance.timing.domInteractive - performance.timing.responseStart)" in devTools

5. yarn make
6. open out/my-app-darwin-arm64/my-app
7. run "console.log(performance.timing.domInteractive - performance.timing.responseStart)" in devTools

compare the time on first launch and console.log
