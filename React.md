# What’s new in React 18?

1. Root API
2. Automatic batching

3. Concurrent rendering

4. Suspense Features

5. New Hooks
  1. useId
  2. useTransition
  3. useDeferredValue
  4. useSyncExternalStore
  5. useInsertionEffect
  
6. Concurrent React Features in Strict Mode
- React 18 enhances Strict Mode to help developers find concurrency-related bugs by simulating unmounting and remounting components more aggressively.

7. Automatic useEffect Cleanup
- React 18 automatically runs the cleanup function of the useEffect hook before a new effect is run. This change ensures that cleanup happens before a new effect is applied, which can help prevent bugs in concurrent environments.



