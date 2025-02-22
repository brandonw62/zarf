# zarf tools registry copy
<!-- Auto-generated by docs/gen-cli-docs.sh -->

Efficiently copy a remote image from src to dst while retaining the digest value

```
zarf tools registry copy SRC DST [flags]
```

## Options

```
      --all-tags     (Optional) if true, copy all tags from SRC to DST
  -h, --help         help for copy
  -j, --jobs int     (Optional) The maximum number of concurrent copies, defaults to GOMAXPROCS
  -n, --no-clobber   (Optional) if true, avoid overwriting existing tags in DST
```

## Options inherited from parent commands

```
  -a, --architecture string   Architecture for OCI images and Zarf packages
      --insecure              Allow access to insecure registries and disable other recommended security enforcements such as package checksum and signature validation. This flag should only be used if you have a specific reason and accept the reduced security posture.
  -l, --log-level string      Log level when running Zarf. Valid options are: warn, info, debug, trace (default "info")
      --no-log-file           Disable log file creation
      --no-progress           Disable fancy UI progress bars, spinners, logos, etc
      --tmpdir string         Specify the temporary directory to use for intermediate files
      --zarf-cache string     Specify the location of the Zarf cache directory (default "~/.zarf-cache")
```

## SEE ALSO

* [zarf tools registry](zarf_tools_registry.md)	 - Tools for working with container registries using go-containertools
