# UCLA Chi Epsilon Website

## Writing new content and committing

1. Run `git status`. This shows you if you have made any changes.
2. Run `git add -A` to tell git to add all current changes for the next commit.
3. Run `git commit` to commit all changes locally.
4. Run `git push` to upload your changes onto github.

## Building and updating the website

1. Run `hugo` to build the site. New files will be located in the `public/`
   directory.
2. Copy all the files in `public/` to the `uclachiepsilon.github.io` directory.
3. Go to the `uclachiepsilon.github.io` directory and run `git status`, `git
   add -A`, `git commit`, and `git push` to upload those changes so that they
   are viewable on https://uclachiepsilon.github.io.
