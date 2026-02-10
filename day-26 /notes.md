## Modified some codes and starte learning about `Typescript`

* added `const review_code=require("./services/git.services")` inside the file calling review_code function.
* instead of checking if its a git_repo or not checking if it's git  root repo or not by replacing the exec command by   `"git", ["rev-parse", "--show-toplevel"],`
* Added git_branch_exists function to the `git.services` to check if the branch exists.
* TypeScript is a programming language that enhances JavaScript by adding static typing, helping developers catch errors early and build more reliable applications.