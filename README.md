# React useEffect Hook Not Updating on State Change

This example demonstrates a common mistake when using the `useEffect` hook in React.  The provided `useEffect` hook has an empty dependency array (`[]`), meaning it will only run once after the initial render.  This prevents the console log from updating as the state changes.

The solution demonstrates the correct usage of `useEffect` to log the changes in state.