# What is this?

Get perfect shadows every time for the non-designer.

# Installation

`npm i box-shadowizard --save`

Then...

````
import { shadowizard } from 'box-shadowizard';

shadowizard(({
    shadow__type: 'soft',
    padding: false
}));

````

## Options

Shadowizard support 2 options, both of which are optional:

* *shadow_type* -_hard | soft_ (defaults to soft)
* *padding* -_boolean_ (default to false)