# Cross-origin communication POC

This repo showcases cross-origin communication using postMessage api.

## Architecture

Cross-origin communication is simulated using two projects:

- simple web page for hosting the iframe
- webapp to open in new tab  

### for frameworks

The same rule you must follow when you use JavaScript frameworks like Vue, React, Angular or any other framwework. But remember! When using frameworks you can’t mount to normal window “load” event listener. You must use LIFECYCLE HOOKS of certain framework.
