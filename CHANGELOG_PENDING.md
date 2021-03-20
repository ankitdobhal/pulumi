### Breaking


### Improvements

- [cli] Improve diff displays during `pulumi refresh`
  [#6568](https://github.com/pulumi/pulumi/pull/6568)

- [sdk/go] Cache loaded configuration files.
  [#6576](https://github.com/pulumi/pulumi/pull/6576)

- [automation/*] Implement minimum version checking and add:
  - Go: `LocalWorkspace.PulumiVersion()` - [#6577](https://github.com/pulumi/pulumi/pull/6577)
  - Nodejs: `LocalWorkspace.pulumiVersion` - [#6580](https://github.com/pulumi/pulumi/pull/6580)
  - Python: `LocalWorkspace.pulumi_version` - [#6589](https://github.com/pulumi/pulumi/pull/6589)
  - Dotnet: `LocalWorkspace.PulumiVersion` - [#6590](https://github.com/pulumi/pulumi/pull/6590)
  
### Bug Fixes

