# Goal of this POC

This repository is a repro of an error preventing viro from running on simulators event with no viro component being called.

# Getting started

```sh
yarn
npx pod-install
yarn start
yarn ios
```

You should see a crash report from the simulator with this error:
 
```
Termination Reason: DYLD 1 Library missing
Library not loaded: @rpath/GTMSessionFetcher.framework/GTMSessionFetcher
```
