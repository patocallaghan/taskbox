# Testing `inPercy` with a Storybook + @percy/storybook 4.x integration

Run the following command

```js
yarn percy storybook:start --port=9009 --static-dir=./public --verbose
```

The primary button should be blue in the local storybook but purple when snapshotted in Percy.