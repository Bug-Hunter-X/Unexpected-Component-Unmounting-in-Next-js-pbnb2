# Unexpected Component Unmounting in Next.js

This repository demonstrates a bug where a Next.js component unmounts unexpectedly when navigating between pages. The component uses `useState` and `useEffect` hooks, and its unmounting behavior is not correctly managed.  This leads to console errors and broken functionality.

## Bug Description
The `MyComponent` unexpectedly unmounts when navigating away from the page.  This causes the cleanup function in `useEffect` to log, but it shouldn't under normal circumstances if the component is properly managed.

## Solution
The solution involves carefully reviewing the component's lifecycle and data management. This example includes no specific changes as the provided code is functional but demonstrates an expected behavior.