# rote

A flashcard app for Landscape.

## Installation

Create an `.urbitrc` file:

```js
module.exports = {
  URBIT_PIERS: [
    "/path/to/ship/home",
  ]
};
```

Then, in Unix:

```
yarn
yarn run build
```

Then, in Dojo:

```
|commit %home
|start %rote
```

## Walkthrough

This repository also functions as a walkthrough for creating your own Gall
app! Open up [rote.hoon](urbit/app/rote.hoon) and read the whole thing.