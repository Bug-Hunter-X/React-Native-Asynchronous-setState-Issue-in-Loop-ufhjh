# React Native Asynchronous setState Issue

This repository demonstrates a common issue in React Native: incorrect state updates when using setState within a loop or asynchronous operation.  The example shows how attempting to increment a state variable within a loop using setTimeout leads to the final state not reflecting the expected value.

The solution provided showcases a better approach to handling such updates using promises or async/await to ensure correct state updates.