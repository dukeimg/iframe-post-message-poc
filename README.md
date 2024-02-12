# postMessage POC

This repo showcases iframe communication using postMessage api.

It features two examples:
- simple handshake example 
- advanced message passing example 

Ts config will be used if more intricate examples are needed.

## start

To run simple:
```sh
open src/parent.html in browser
```

To run:
```sh
open src/advanced/parent.html in browser
```

### postMessage for frameworks

Remember, When using frameworks you can’t mount to normal window “load” event listener. You must use lifecycle hooks.
