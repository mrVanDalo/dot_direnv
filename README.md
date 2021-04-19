My collection of direnv setups
which I use all the time.

Here is an example on what I put in an .envrc of a terraform project

```sh
export PROJECT_ROOT=`realpath ../../`
source_env "$PROJECT_ROOT/.envrc"
source_env ~/direnv/.envrc
```
