---
type: docs
title: "rad group list CLI reference"
linkTitle: "rad group list"
slug: rad_group_list
url: /reference/cli/rad_group_list/
description: "Details on the rad group list Radius CLI command"
---
## rad group list

List resource groups within current/specified workspace

### Synopsis

List resource groups within current/specified workspace
	
	Resource groups are used to organize and manage Radius resources. They often contain resources that share a common lifecycle or unit of deployment.
			
	A Radius Application and its resources can span one or more resource groups, and do not have to be in the same resource group as the Radius Environment into which it's being deployed into.
			
	Note that these resource groups are separate from the Azure cloud provider and Azure resource groups configured with the cloud provider.

```
rad group list [flags]
```

### Examples

```
rad group list
```

### Options

```
  -h, --help               help for list
  -o, --output string      output format (supported formats are json, table) (default "table")
  -w, --workspace string   The workspace name
```

### Options inherited from parent commands

```
      --config string   config file (default "$HOME/.rad/config.yaml")
```

### SEE ALSO

* [rad group]({{< ref rad_group.md >}})	 - Manage resource groups

