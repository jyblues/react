* Problem : 
```
Module not found: Error: Cannot resolve module 'react/lib/ReactMount'
```

* Solution
```
resolve: {
      alias: {
          'react/lib/ReactMount': 'react-dom/lib/ReactMount',
          'react/lib/ReactTestUtils': 'react-dom/lib/ReactTestUtils'
      }
  }
```
