This is extracted from NavigationExperimental in react-native 0.42.0. All the require path is been localized, so it can function as a standalone module in react native project.

The motivation of this is that NavigationExperimental will be deprecated soon, but the alternative one (react-navigation) is not stable enough.

To use:

```js
// change
import { NavigationExperimental } from 'react-native';
// to
import * as NavigationExperimental from 'navigation-experimental';
```