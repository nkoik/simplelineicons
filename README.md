# Simple Line Icons as a Vue Component

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/ce117e5563a14a49b560e407b8d81e8b)](https://app.codacy.com/app/nkoik/simplelineicons?utm_source=github.com&utm_medium=referral&utm_content=nkoik/simplelineicons&utm_campaign=badger)

This is a Vue wrapper component for simple line icons fonts.
https://github.com/thesabbir/simple-line-icons/


## ✔ Installation

Get the package:
```bash
npm install vue-simple-line
```

## ✔ Use

Register SimpleLineIcons in your app:
```js
In main.js
import Vue from 'vue'
import SimpleLineIcons from 'vue-simple-line'

Vue.component('simple-line-icons', SimpleLineIcons)

OR In component

new Vue({
    components: {
        SimpleLineIcons
    }
})
```

In your template you can call it like this:

```html
<simple-line-icons
	icon="plus"
	:rotate="90"
	size="small"
	color="mediumseagreen">
</simple-line-icons>
```
### API

Required Prop

| Property | Description | Type
|:--|:--|:--|
| icon | Contains the name of the icon | <i>String</i> |

Optional Props

| Property | Description | Type
|:--|:--|:--|
| rotate | The degrees of rotation | <i>Number</i> |
| size | The size of the icon. Values <b>small</b> OR <b>large</b> | <i>String</i> |
| color | Any hex,rgb,hsla color | <i>String</i> |

