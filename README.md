
## 💾 Requirements

* `Web Browser` - Can be used as an emulator to build applications. Example [Chrome, Firefox, Safari & Opera].
* `Internet` - Because many use CDN and to make it easier to find solutions to all problems.

## 🎯 How To Use

#### Example Syntax

```javascript
const { debounce, throttle } = require('./src/debounceThrottle');

// Example of using debounce function
const debouncedFunction = debounce(() => {
    console.log('Debounced function called');
}, 200);

// Example of using throttle function
const throttledFunction = throttle(() => {
    console.log('Throttled function called');
}, 200);

// Call the debounced function
debouncedFunction(); // This will not trigger immediately

// Call the throttled function
throttledFunction(); // This will trigger immediately
```

#### Explanation

* `Debounce Function`: Debouncing ensures that a function will not be called more often than a specified interval of time. It is typically used when you want to wait for some time after the last call to the function before executing it.
* `Throttle Function`: Throttling limits the rate at which a function can be called. It ensures that a function is called at most once during an interval of time. Throttling is useful when you want to ensure that a function is not called more frequently than a specified frequency.

#### Return Value

* Both debounce and throttle functions return a new function that encapsulates the original function and its behavior. This returned function can then be used to execute the original function with the specified debouncing or throttling behavior.

