# Incorrect State Update in useEffect Hook

This example demonstrates a common error in React's `useEffect` hook where the component's state is updated directly instead of using the setter function.  This will not trigger a re-render and will result in unexpected behavior.

**The bug:** Direct mutation of state variable inside `useEffect` hook. 

**Solution:** Use the `setCount` function to update the state correctly. This ensures React re-renders the component to reflect the changes.