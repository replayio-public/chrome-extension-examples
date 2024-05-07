# Sample Chrome extension

## Steps to record the extension

1. Install the replay browser
```sh
npx replayio update
```

2. Record a replay that uses the extension
```sh
RECORD_ALL_CONTENT=1 ~/.replay/runtimes/Replay-Chromium.app/Contents/MacOS/Chromium --load-extension=./extension
```

3. Upload the replay

```sh
npx replayio upload
```
