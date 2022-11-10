### Javascript import / export cheat sheet

#### Name Export | Name Import
```
export const name = 'value'
import { name } from '...'
```

#### Default Export | Default Import
```
export default 'value'
import anyName from '...'
```

#### Rename Export | Name Import
```
export { name as newName }
import { newName } from '...'
```

#### Name + Default | Name Import All
```
export const name = 'value'
export default 'value'
import * as anyName from '...'
```

#### Export List + Rename | Import List + Rename
```
export { 
  name1
  name2 as newName2
}
import {
  name1 as newName1,
  newName2
} from '...'
```
