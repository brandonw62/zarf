# zarf tools sbom login
<!-- Auto-generated by docs/gen-cli-docs.sh -->

Log in to a registry

```
zarf tools sbom login [OPTIONS] [SERVER] [flags]
```

## Options

```
  -h, --help              help for login
  -p, --password string   Password
      --password-stdin    Take the password from stdin
  -u, --username string   Username
```

## Options inherited from parent commands

```
  -a, --architecture string   Architecture for OCI images and Zarf packages
  -c, --config string         application config file
      --insecure              Allow access to insecure registries and disable other recommended security enforcements such as package checksum and signature validation. This flag should only be used if you have a specific reason and accept the reduced security posture.
  -l, --log-level string      Log level when running Zarf. Valid options are: warn, info, debug, trace (default "info")
      --no-log-file           Disable log file creation
      --no-progress           Disable fancy UI progress bars, spinners, logos, etc
  -q, --quiet                 suppress all logging output
      --tmpdir string         Specify the temporary directory to use for intermediate files
  -v, --verbose count         increase verbosity (-v = info, -vv = debug)
      --zarf-cache string     Specify the location of the Zarf cache directory (default "~/.zarf-cache")
```

## SEE ALSO

* [zarf tools sbom](zarf_tools_sbom.md)	 - Generates a Software Bill of Materials (SBOM) for the given package
