## Intl.UnitFormat API Specification [draft]

### Status

__Stage 1__

Implementation Progress

 * Polyfill: https://github.com/zbraniecki/IntlUnitFormat

Backpointers

* https://github.com/tc39/ecma402/issues/32
* http://cldr.unicode.org/translation/units

### Authors

 * Zibi Braniecki (@zbraniecki)

### Reviewers

TBD

### Informative

This proposal is based on the LDML spec, List Patterns:


### Prior Art


### Usage

```javascript
let o = new Intl.UnitFormat("en", {
    type: "duration",
    unit: "hour",
    style: "long" // default style
});
console.log(o.format(15)); // "15 hours"
```

### Render Spec

```bash
npm install
npm run build
open index.html
```
