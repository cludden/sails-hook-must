# sails-hook-must
a `sails` hook that replaces the default `policy` hook. This simply augments the default `policy` hook by auto-building any `sails-must` policies. For more info, see [sails-must](https://github.com/cludden/sails-must)

## Installing
Install via `npm`:
`npm install --save sails-hook-must`

Disable the default `policy` hook:
```javascript
// in config/hooks.js

module.exports.hooks = {
    policies: false
}
```
