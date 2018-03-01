# concrete-sign
A concrete sign, where chalk letters are moved using Arduino and servos.

This repo contains code and material for an experiment I'll be building, made out of chalk letters installed on servos and synced via Arduino.

___
#### How to run
You need an arduino board with Frimata flashed on it to run this code. (Can be done trough the default IDE)

Install deps: `yarn install`
Run the code: `node ./index.js`

You will be presented with a REPL prompt which exposes a `letters` array.
This array will contain instances of [`Letter`](https://github.com/ghzmdr/concrete-sign/src/Letter.js) which can be used to move the servos around.

![Welcome Prompt](https://raw.githubusercontent.com/ghzmdr/concrete-sign/develop/docs/img/repl_injectables.png)
___
#### Current Stage:

- Prototyping:
    + I'm exploring how I could manage the servos via code and which circuitery is needed.
    **Deliverable**: At least 2 letters in scale made out of cardboard

___
![Rotating smurf with Servo](https://raw.githubusercontent.com/ghzmdr/concrete-sign/develop/docs/img/rotating_smurf.gif)

___
