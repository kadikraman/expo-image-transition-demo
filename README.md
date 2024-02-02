## Expo Image Transition

This is a demo to show a curious behaviour with Expo Image: when you navigate between screens, the transition gets run every time though the screen does not re-render.

```sh
yarn
yarn start
```

To repro, navigate between screens: observe that the image always re-renders when you go between Tab1 and Tab2 although the `console.log` only gets run the first time.