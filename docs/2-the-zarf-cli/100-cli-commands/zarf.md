# zarf
<!-- Auto-generated by docs/gen-cli-docs.sh -->

DevSecOps for Airgap

## Synopsis

Zarf eliminates the complexity of air gap software delivery for Kubernetes clusters and cloud native workloads
using a declarative packaging strategy to support DevSecOps in offline and semi-connected environments.

```
zarf COMMAND [flags]
```

## Options

```
  -a, --architecture string   Architecture for OCI images and Zarf packages
  -h, --help                  help for zarf
      --insecure              Allow access to insecure registries and disable other recommended security enforcements such as package checksum and signature validation. This flag should only be used if you have a specific reason and accept the reduced security posture.
  -l, --log-level string      Log level when running Zarf. Valid options are: warn, info, debug, trace (default "info")
      --no-log-file           Disable log file creation
      --no-progress           Disable fancy UI progress bars, spinners, logos, etc
      --tmpdir string         Specify the temporary directory to use for intermediate files
      --zarf-cache string     Specify the location of the Zarf cache directory (default "~/.zarf-cache")
```

## SEE ALSO

* [zarf completion](zarf_completion.md)	 - Generate the autocompletion script for the specified shell
* [zarf connect](zarf_connect.md)	 - Accesses services or pods deployed in the cluster
* [zarf destroy](zarf_destroy.md)	 - Tears down Zarf and removes its components from the environment
* [zarf init](zarf_init.md)	 - Prepares a k8s cluster for the deployment of Zarf packages
* [zarf package](zarf_package.md)	 - Zarf package commands for creating, deploying, and inspecting packages
* [zarf prepare](zarf_prepare.md)	 - Tools to help prepare assets for packaging
* [zarf tools](zarf_tools.md)	 - Collection of additional tools to make airgap easier
* [zarf version](zarf_version.md)	 - Shows the version of the running Zarf binary
