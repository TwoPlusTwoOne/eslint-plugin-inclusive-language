## Contributing

1. Familiarize yourself with the codebase.
1. Create a new issue before starting your project so that I can keep track of what you are trying to add/fix. That way, I can also offer suggestions or let you know if there is already an effort in progress. I will let you know when you're good to go to start.
1. Fork this repository.
1. The [README](README.md) has details on how to set up your environment.
1. Create a _topic_ branch in your fork based on the correct branch (usually the **primary** branch. Note, this step is recommended but technically not required if contributing using a fork.
1. Edit the code in your fork.
1. Send us a pull request when you are done. I'll review your code, suggest any
   needed changes, and merge it in.

## Branches

-   I work in `primary`.
-   Released (aka. _production_) branch is `primary`.
-   Work happens in _topic_ branches (feature and/or bug-fix).
    -   feature as well as bug-fix branches are based on `primary`
    -   branches _should_ be kept up-to-date using `rebase`
    -   see below for further merge instructions

### Merging between branches

-   I try to limit merge commits as much as possible.

-   _Topic_ branches are:

    1. based on `primary` and will be
    1. squash-merged into `primary`.

## Pull Requests

-   Develop features and bug fixes in _topic_ branches.
-   _Topic_ branches can live in forks (external contributors) or within this repository (committers).
    \*\* When creating _topic_ branches in this repository please prefix with `<developer-name>/`.

### Merging Pull Requests

-   Pull request merging is restricted to squash & merge only.