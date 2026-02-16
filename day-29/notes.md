## worked on lint fixing
* lint fix Fixes all the autofixable errors such as semicolons, indentation, spacing, and other small formatting issues to make the code cleaner.
* Lint fixing does not fix logical errors in the code, though sometimes it may resolve minor logical issues accidentally.
* `npx`:Searches for the package locally (inside node_modules) and globally.
If the package is not found, it downloads it temporarily and runs it.
* `npm`:Installs packages listed inside package.json scripts or dependencies.
* To fix all lintable files in your project:
`npx eslint . --ext .ts,.tsx,.js --fix`
