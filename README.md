# Test Functions Provider
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Frlfagan%2Fterraform-provider-testfunctions.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Frlfagan%2Fterraform-provider-testfunctions?ref=badge_shield)


This repository is a Terraform provider for testing purposes. It is not intended for production use.

## Requirements

- [Terraform](https://developer.hashicorp.com/terraform/downloads) >= 1.8
- [Go](https://golang.org/doc/install) >= 1.21

## Building The Provider

1. Clone the repository
1. Enter the repository directory
1. Build the provider using the Go `install` command:

```shell
go install
```

## Using the provider

This provider is not intended for production use. It is intended for testing purposes only.

TODO:

## Developing the Provider

If you wish to work on the provider, you'll first need [Go](http://www.golang.org) installed on your machine (see [Requirements](#requirements) above).

To compile the provider, run `go install`. This will build the provider and put the provider binary in the `$GOPATH/bin` directory.

To generate or update documentation, run `go generate`.

In order to run the full suite of Acceptance tests, run `make testacc`.

*Note:* Acceptance tests create real resources, and often cost money to run.

```shell
make testacc
```


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Frlfagan%2Fterraform-provider-testfunctions.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Frlfagan%2Fterraform-provider-testfunctions?ref=badge_large)