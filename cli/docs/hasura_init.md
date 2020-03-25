## hasura init

Initialize directory for Hasura GraphQL Engine migrations

### Synopsis

Create directories and files required for enabling migrations on Hasura GraphQL Engine

```
hasura init [flags]
```

### Examples

```
  # Create a directory to store migrations
  hasura init

  # Now, edit <my-directory>/config.yaml to add endpoint and access key

  # Create a directory with endpoint and access key configured:
  hasura init --directory <my-project> --endpoint https://my-graphql-engine.com --access-key secretaccesskey

  # See https://docs.hasura.io/1.0/graphql/manual/migrations/index.html for more details
```

### Options

```
      --access-key string   access key for Hasura GraphQL Engine
      --directory string    name of directory where files will be created
      --endpoint string     http(s) endpoint for Hasura GraphQL Engine
  -h, --help                help for init
```

### Options inherited from parent commands

```
      --log-level string   log level (DEBUG, INFO, WARN, ERROR, FATAL) (default "INFO")
      --project string     directory where commands are executed. (default: current dir)
```

### SEE ALSO

* [hasura](hasura.md)	 - Hasura GraphQL Engine command line tool

###### Auto generated by spf13/cobra on 28-Sep-2018