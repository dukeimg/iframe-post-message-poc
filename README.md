# postMessage POC

This repo showcases iframe communication using postMessage api.

It features two examples:
- simple handshake example (src/parent)
- advanced message passing example (src/advanced/parent)

Ts config will be used if more intricate examples are needed.

## start

To set up server:
```sh
install live server vscode extension
```

To run:
```sh
open parent with live server using command pallate or right click
```

### postMessage for frameworks

Remember, When using frameworks you can’t mount to normal window “load” event listener. You must use lifecycle hooks.
