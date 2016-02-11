# gitflow-incremental-builder

- Returns names of maven modules which contain changes compared to "origin/develop" branch.
- Useful for multi-module maven projects using Gitflow model, where "origin/develop" is always stable.
- Don't forget to fetch first.

## Example Bash Execution

``` mvn -amd -pl "$(gib.sh pom.xml)" --file pom.xml ```

Builds compared to "origin/develop" modules containing changes and all their dependents.

## Last Release

https://github.com/vackosar/gitflow-incremental-builder/raw/master/release/gitflow-incremental-builder-1.1-bin.zip