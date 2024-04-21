### PassGenerator 

This is a small project to learn how react hooks works.
In this project we can learn how react useEffect, useCallback and useState works also useRef is used to add reference between two elements.
useCallback:
It is a hook used for memoization purpose, it optimises the performance react code.
It takes two parameters as input one is a function value that you want to cache and other is array o dependencies:These are  often paramters of function used by useCallback.It can be used for:
Skipping re-rendering of components
Updating state from a memoized callback

useEffect:

Every time your component renders, React will update the screen and then run the code inside useEffect. In other words, useEffect “delays” a piece of code from running until that render is reflected on the screen. This can be useful for performing side effects in function components. For example, you might use useEffect to fetch data from an API, subscribe to a WebSocket, or set up event listeners. By default, useEffect runs after every render, including the initial render. However, you can control when it runs by providing dependencies as the second argument to useEffect. If the dependencies change between renders, useEffect will run again. If you don't specify any dependencies, useEffect will run after every render.

useRef:
When you want a component to “remember” some information, but you don’t want that information to trigger new renders, you can use a ref.Call the useRef Hook and pass the initial value that you want to reference as the only argument useRef returns an object like this: 
```javascript
{
current:value you pass to your ref
}
```
It’s like a secret pocket of your component that React doesn’t track.
useState:
It is most common and simle hook use to set or reset any specific value/targeted-value of a component.React uses this hook to render change only on that target element without re-rendering of page. 
