# Charts

![Build](https://github.com/lab42/Charts/actions/workflows/build.yml/badge.svg?branch=main)

Charts are build automatically and served via Github Pages.

Be aware that these charts should be designed for usage with Skaffold.

    * Always use `task lint` before pushing
    * Make sure you add a new package to the package list in Taskfile.yml
 
## Adding the Helm repo

`helm repo add lab42 https://lab42.github.io/Charts/`
