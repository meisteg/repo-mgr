# Git Repository Manager

Simple tool for assisting git repository dependencies.

## Usage

```
 ./repo-mgr.sh <command> [OPTIONS]
  Commands:
      init - Initialize repositories
```

### init

- `-f <file>` - Specify file with repo information
- `-z` - By default, existing directories are skipped. This flag can be used to force the init by removing the existing directory. USE THIS FLAG WITH CAUTION - CAN LOSE DATA!
