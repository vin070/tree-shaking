### ECMAScript import
```
const {add, multiply} = require('@vineet4b/tree-shaking-demo/math')
const {capitalize, lowercase} = require('@vineet4b/tree-shaking-demo/string')
const {add, multiply,capitalize, lowercase} = require('@vineet4b/tree-shaking-demo')

```

### CommonJS import
```
import {add, multiply} from  '@vineet4b/tree-shaking-demo/math';
import {capitalize, lowercase} from  '@vineet4b/tree-shaking-demo/string'
import {add, multiply,capitalize, lowercase} from  '@vineet4b/tree-shaking-demo'
```