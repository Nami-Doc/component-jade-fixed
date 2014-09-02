Component-Jade-Fixed
====================

## Only for component < 1.0.0


### Install

```
# the module to --use
npm install component-jade-fixed
# depends on the jade runtime -- only needed if you use the .scripts
component install component-jade-fixed
```

### Usage

`component.json` :

```
{
  // - Require a Jade function
  // usage : div.innerHTML = require('./template.html')({my: 'arguments'})
  "scripts": ["template.jade"],

  // - Require a HTML string
  // usage : div.innerHTML = require('./tmpl-html.html')
  "templates": ["tmpl-html.jade"]
}
```
