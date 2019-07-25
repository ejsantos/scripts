# Dump of scripts

## giti
Checks if SHA is present in a branch
 ```sh
  giti <SHA> ## => checks if SHA is present in the current checked out branch
  giti <SHA> <BRANCH/TAG> ## => checks if SHA is present in the given branch/tag
```

## check-and-restart-component
Checks and restarts HDP components install via Ambari and restarts it if:
- not running
- not in maintenance mode
- node is healthy
```sh
  check-and-restart-component ## => displays help message with a list of valid components
  check-and-restart-component --component=<VALID_COMPONENT>  ## => checks all host if the component is installed and restarts if the above criteria were met
  ```
