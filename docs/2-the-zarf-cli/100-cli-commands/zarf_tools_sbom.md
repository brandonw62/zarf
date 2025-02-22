# zarf tools sbom
<!-- Auto-generated by docs/gen-cli-docs.sh -->

Generates a Software Bill of Materials (SBOM) for the given package

## Synopsis

Generate a packaged-based Software Bill Of Materials (SBOM) from container images and filesystems

```
zarf tools sbom [flags]
```

## Options

```
      --catalogers stringArray   enable one or more package catalogers
  -c, --config string            application config file
      --exclude stringArray      exclude paths from being scanned using a glob expression
      --file string              file to write the default report output to (default is STDOUT)
  -h, --help                     help for sbom
      --name string              set the name of the target being analyzed
  -o, --output stringArray       report output format, options=[syft-json cyclonedx-xml cyclonedx-json github-json spdx-tag-value spdx-json syft-table syft-text template] (default [syft-table])
      --platform string          an optional platform specifier for container image sources (e.g. 'linux/arm64', 'linux/arm64/v8', 'arm64', 'linux')
  -q, --quiet                    suppress all logging output
  -s, --scope string             selection of layers to catalog, options=[Squashed AllLayers] (default "Squashed")
  -t, --template string          specify the path to a Go template file
  -v, --verbose count            increase verbosity (-v = info, -vv = debug)
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

* [zarf tools](zarf_tools.md)	 - Collection of additional tools to make airgap easier
* [zarf tools sbom attest](zarf_tools_sbom_attest.md)	 - Generate an SBOM as an attestation for the given [SOURCE] container image
* [zarf tools sbom convert](zarf_tools_sbom_convert.md)	 - Convert between SBOM formats
* [zarf tools sbom login](zarf_tools_sbom_login.md)	 - Log in to a registry
* [zarf tools sbom packages](zarf_tools_sbom_packages.md)	 - Generate a package SBOM
* [zarf tools sbom version](zarf_tools_sbom_version.md)	 - show the version
