<p align="center">
    <a href="https://travis-ci.org/Cobertos/vue-contenteditable-input" target="_blank"><img alt="build status" src="https://travis-ci.org/Cobertos/vue-contenteditable-input.svg?branch=master"></a>
    <a href="https://twitter.com/cobertos" target="_blank"><img alt="twitter" src="https://img.shields.io/badge/twitter-%40cobertos-0084b4.svg"></a>
    <a href="https://cobertos.com" target="_blank"><img alt="twitter" src="https://img.shields.io/badge/website-cobertos.com-888888.svg"></a>
</p>

# input-contenteditable

Vue component wrapping `contenteditable` with all the features you expect from `input[type='text']`.

Supports:
 * v-model
 * placeholder
 * maxlength

## Usage

```
<input-contenteditable
    v-model="someModel"
    :placeholder="myPlaceHolder"
    :maxlength="22" />
```

### Developing
#### Testing

```
npm run test:unit
npm run test:unit -- --watch
npm run lint --no-fix
...
```
