---
date: 2019-05-17T14:07:47Z
title: "jx step create"
slug: jx_step_create
url: /commands/jx_step_create/
---
## jx step create

create [command]

### Synopsis

create [command]

```
jx step create [flags]
```

### Options

```
  -h, --help   help for create
```

### Options inherited from parent commands

```
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --log-level string          Sets the logging level (panic, fatal, error, warning, info, debug) (default "info")
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx step](/commands/jx_step/)	 - pipeline steps
* [jx step create jenkins](/commands/jx_step_create_jenkins/)	 - Creates the Jenkins config.xml file from a number of ConfigMaps for Pod Templates
* [jx step create task](/commands/jx_step_create_task/)	 - Creates a Tekton Pipeline Run for the current folder or given build pack
* [jx step create version](/commands/jx_step_create_version/)	 - Creates a Pull Request on the versions git repository for a new version of a chart/package

###### Auto generated by spf13/cobra on 17-May-2019