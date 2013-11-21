# karma-jasmine

> Adapter for the NUnit testing framework.

## Installation

The easiest way is to keep `karma-nunit` as a devDependency in your `package.json`.
```json
{
  "devDependencies": {
    "karma": "~0.10",
    "karma-nunit": "~0.1"
  }
}
```

You can simple do it by:
```bash
npm install karma-nunit --save-dev
```

## Configuration
```js
// karma.conf.js
module.exports = function(config) {
  config.set({
    frameworks: ['nunit'],

    files: [
      '*.js'
    ]
  });
};
```

For more information on Karma see the [karma].
For more information on NUnit.js go to [nunit].


[karma]: http://karma-runner.github.com
[nunit]: https://github.com/nealxyc/nunit.js
