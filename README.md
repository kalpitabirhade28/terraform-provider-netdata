# Terraform Provider for Netdata Cloud

This is the [Terraform](https://www.terraform.io/) provider for the [Netdata Cloud](https://www.netdata.cloud/).

This provider allows you to install and manage Netdata Cloud resources using Terraform.


## Contents

* [Requirements](#requirements)
* [Getting Started](#getting-started)

## Requirements

- [Terraform](https://www.terraform.io/downloads.html) v1.1.0 or later
- [Go](https://golang.org/doc/install) v1.20 or later (to build the provider plugin)

## Getting Started

* from terraform registry

TODO

* from source code

	* setup your [CLI configuration](https://developer.hashicorp.com/terraform/cli/config/config-file#development-overrides-for-provider-developers)

	```console
	$ cat ~/.terraformrc
	provider_installation {
  		dev_overrides {
		    # TODO: Update this string with the published name of your provider
  		    "netdata.cloud/todo/netdata" = "<your GOBIN directory>"
  		}
  		direct {}
	}
	```

	* build the provider

	```console
	$ make local-build
	```
