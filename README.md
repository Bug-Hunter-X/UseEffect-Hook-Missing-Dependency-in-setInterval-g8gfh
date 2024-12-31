# React useEffect Hook Missing Dependency in setInterval

This repository demonstrates a common error in React's `useEffect` hook: missing a dependency in the dependency array when using `setInterval`. This leads to an infinite loop, as the effect runs continuously without ever updating its dependency.