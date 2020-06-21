# Debugging: integrate, week 2

The integration exercise this week is slightly more complicated than last week.  The biggest change is using _script variables_ to share values between handler calls:

```txt
.
├── /scripts
│   ├── /script-variables.js
│   └── /handlers
│       ├── /evens-or-odds.js
│       ├── /list-all-numbers.js
│       ├── /range-display.js
│       ├── /range-set.js
│       ├── /repeat-string.js
│       └── /sum-numbers-in-range.js
├── /index.html
├── /LICENSE
├── /README.md
└── /style.css
```

---

## Your Tasks

Most of the code already works, the files you need to work in are listed below. Every other file already works correctly.

### 0. Study the directory structure

Before writing anything, take some time to read through the folders and files.  Understand what code is where and why it's organized the way it is.

### 1. [`index.html`](./index.html): Complete the

### 2. [`sum-numbers-in-range.js`](./scripts/handlers/sum-numbers-in-range.js): Fill in the blanks

### 3. [`list-all-numbers.js`](./scripts/handlers/list-all-numbers.js): Fill in the blanks

### 4. [`repeat-string.js`](./scripts/handlers/repeat-string.js): Fix the bugs

### 4. [`evens-or-odds.js`](./scripts/handlers/evens-or-odds.js): Write the logic

---

## How to DevTool

- Always have your DevTools open.  The debugger will be overwhelming at first, but very quickly you won't know how to work without it.
- Set your debugger to [__pause on exceptions__](https://developers.google.com/web/updates/2015/05/automatically-pause-on-any-exception)
- Carefully read all console output, especially error messages. Errors aren't failure they are JavaScript trying to help you!
- Expand errors to practice reading the callstack
- Click on the line numbers to the right of console output to read the source code

## Good Habits

- Test your code __all the time__.  Every time you make any changes, click the button to see what changed
- Make one change at a time. If you make many changes at once it's hard to know which one made a difference.

So a good workflow will be something like this (after the project is open in your browser):

1. Click on the button you are studying
1. Step through the handler in your debugger until you reach an error or something that does not work correctly
1. Go to VSCode and make one small change to try fixing the bug, save your changes!
1. Return to the browser, refresh, and click the same button
1. Step through to the line of code that caused problems last time, is it fixed?
1. repeat!
