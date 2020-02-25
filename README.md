A basic Alexa skill using [Alexa Skills Kit SDK for Node.js](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs) together with their [ASK SDK Express Adapter](https://github.com/alexa/alexa-skills-kit-sdk-for-nodejs/tree/2.0.x/ask-sdk-express-adapter), modifying [this](https://github.com/alexa/skill-sample-nodejs-hello-world) example.

## Changes made to the [source](https://github.com/alexa/skill-sample-nodejs-hello-world/tree/master/lambda/custom) in order to support the Express Adapter
- renamed `index.js` to `skill.js`
- removed `.lambda()` at the bottom of `skill.js`
- added **Express** stuff to a new `index.js`
