# @jsreport/jsreport-sample-template
[![NPM Version](http://img.shields.io/npm/v/@jsreport/jsreport-sample-template.svg?style=flat-square)](https://npmjs.com/package/@jsreport/jsreport-sample-template)

**jsreport extension which creates sample templates at the first run**

## Configuration

```js
"extensions": {
  "sample-template": {
    /* when true, it will create defined samples*/
    "createSamples": true,
    /*
      by default samples will be created only on the first run of your jsreport installation,
      when this option is true it will allow to create the samples in the next run
      (useful when you want to install a new version of this extension and want to create the new examples that come with it)
    */
    "forceCreation": false
  }
}
```

## Changelog

### 3.1.0

- update samples

### 3.0.0-beta.1

Adaptations for the v3 APIs
