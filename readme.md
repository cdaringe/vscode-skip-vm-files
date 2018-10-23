# problem

`vscode` does not allow the user to ignore `VM*` named files, created by `eval`'d code.

# usage/demo

- open `index.js`
- set breakpoints
- run the launch configuration
- try to step over the `eval` code
  - observed that you are brought into a `VM` file

**note** sometimes i found that vscode would not honor my first breakpoint.  that's a seperate issue entirely!