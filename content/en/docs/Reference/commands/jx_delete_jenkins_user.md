---
date: 2019-02-23T09:01:28Z
title: "jx delete jenkins user"
slug: jx_delete_jenkins_user
url: /commands/jx_delete_jenkins_user/
---
## jx delete jenkins user

Deletes one or more Jenkins user API tokens

### Synopsis

Deletes one or more Jenkins user tokens from your local settings

```
jx delete jenkins user [flags]
```

### Examples

```
  # Deletes the current Jenkins token
  jx delete jenkins user admin
```

### Options

```
  -h, --help          help for user
  -n, --name string   The name of the Git server to add a user
  -u, --url string    The URL of the Git server to add a user
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input
      --headless                  Runs in headless mode when using browser automation
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx delete jenkins](/commands/jx_delete_jenkins/)	 - Deletes one or more Jenkins resources

###### Auto generated by spf13/cobra on 23-Feb-2019