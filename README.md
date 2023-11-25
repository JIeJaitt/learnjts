## Purpose

Learnjts is a JavaScript utility library containing a variety of commonly used utility methods.

Learnjts consists of utility methods that I frequently use in real projects. It is a compilation born out of the need for practical tools during development, and also serves as a personal effort to deepen my understanding of JavaScript. In the project, I have provided extensive comments, documenting the thoughts and steps behind the implementations.

By incorporating Learnjts into your projects, you not only gain access to a set of useful utilities but can also leverage this documentation to enhance your understanding of JavaScript.

## Installation

```js
npm i @jiejaitt/learnjts
```

To install Learnjts, run the above command in your project directory. This will add the Learnjts library to your project's dependencies, making it available for use in your JavaScript applications.

## Usage

```js
// First, import the necessary method
import getDataType from '@jiejaitt/learnjts';

// Then, use it directly
getDataType(100) // will return 'number'
```

To utilize Learnjts in your project, begin by importing the required methods. Afterward, you can seamlessly incorporate these methods into your JavaScript code, enhancing your application with the functionality provided by Learnjts.

## Existing Methods and Future Plans

1. **getDataType:** Retrieves the data type of the given variable.
   
2. **capitalNum:** Converts Arabic numerals to their corresponding Chinese counterparts.
   
3. **deepClone:** Performs a deep cloning operation, creating a copy of the provided object or array.
   
4. **debounce:** Implements a debounce mechanism to control the frequency of function calls, reducing the impact of rapid, successive invocations.
   
5. **throttle:** Enforces a throttle mechanism to limit the rate at which a function can be invoked, ensuring a controlled flow of executions.

These are the current methods available in Learnjts. Additionally, there are plans for further expansion and the introduction of new features. Stay tuned for updates!

Please refer to the [Learnjts Documentation](https://jiejaitt.js.org) for detailed information.


## Commit Guidelines

- **feat:** Introduce a new feature.
  
- **fix:** Fix a bug.
  
- **docs:** Only modify documentation.
  
- **style:** Adjust code formatting without altering code logic (e.g., modify spacing, format code, add missing semicolons, etc.).
  
- **refactor:** Refactor code without fixing bugs or adding new features.
  
- **perf:** Optimize performance with code changes aimed at improving efficiency.
  
- **test:** Add or modify code tests.
  
- **chore:** Make changes related to the build process, auxiliary tools, or dependencies (e.g., documentation generation).

Following these commit conventions helps maintain clarity and consistency in version control history. Choose the appropriate type prefix when making commits to better communicate the nature of the changes.

