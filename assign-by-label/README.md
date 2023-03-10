# assign-by-label
Assign or unassign people when labels are added or removed

## Building and developing

- The first time: 
    ```
    npm install
    ```

- When developing: make changes in `src/index.js` or maybe other `js` files in `src/`. Or, for example, add modules to `package.json` using `npm`.

- After every change:
    ```
    npm run build
    ```
    This generates `dist/index.js`, which is the actual script that will be performed by GitHub Actions (it needs to be self-contained in a single file namely, which is what `dist/index.js` is.) Therefore, `dist/index.js` needs to be commited to the repo.

    So if you think you have made a nice change but it is not working, that might be because you forgot this step.
