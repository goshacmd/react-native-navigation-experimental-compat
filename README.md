# NavigationExperimental

NavigationExperimental [has been removed](https://github.com/facebook/react-native/commit/febf3d00ed228391ee4dd6541b0d2746dc56d21f#diff-834d77988fd4294e13e3e35533b3e248) from the React Native codebase.

However, migrating to React Navigation or some other solution might not be easily possible in some projects.

This package is a copy of NavigationExperimental extracted from the react-native repository.

```diff
-import { NavigationExperimental } from 'react-native';
+import NavigationExperimental from 'react-native-navigation-experimental-compat';
```
