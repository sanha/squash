---
title: "squashctl utils delete-permissions"
weight: 5
---
## squashctl utils delete-permissions

remove all service accounts, roles, and role bindings created by Squash.

### Synopsis

remove all service accounts, roles, and role bindings created by Squash.

```
squashctl utils delete-permissions [flags]
```

### Options

```
  -h, --help   help for delete-permissions
```

### Options inherited from parent commands

```
      --container string           Container to debug
      --container-repo string      debug container repo to use (default "soloio")
      --container-version string   debug container version to use (default "mkdev")
      --crisock string             The path to the CRI socket (default "/var/run/dockershim.sock")
      --debugger string            Debugger to use
      --json                       output json format
      --localport int              local port to use to connect to debugger (defaults to random free port)
      --machine                    machine mode input and output
      --namespace string           Namespace to debug
      --no-clean                   don't clean temporary pod when existing
      --no-guess-debugger          don't auto detect debugger to use
      --no-guess-pod               don't auto detect pod to use
      --pod string                 Pod to debug
      --squash-namespace string    the namespace where squash resourcea will be deployed (default: squash-debugger) (default "squash-debugger")
      --timeout int                timeout in seconds to wait for debug pod to be ready (default 300)
```

### SEE ALSO

* [squashctl utils](../squashctl_utils)	 - call various squash utils

