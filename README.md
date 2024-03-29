[![Build Status](https://travis-ci.com/pulumi/pulumi-dnsimple.svg?token=eHg7Zp5zdDDJfTjY8ejq&branch=master)](https://travis-ci.com/pulumi/pulumi-dnsimple)

# dnsimple Resource Provider

The dnsimple resource provider for Pulumi lets you manage dnsimple resources in your cloud programs. To use
this package, please [install the Pulumi CLI first](https://pulumi.io/).

## Installing

This package is available in many languages in the standard packaging formats.

### Node.js (Java/TypeScript)

To use from JavaScript or TypeScript in Node.js, install using either `npm`:

    $ npm install @pulumi/dnsimple

or `yarn`:

    $ yarn add @pulumi/dnsimple

### Python

To use from Python, install using `pip`:

    $ pip install pulumi_dnsimple

### Go

To use from Go, use `go get` to grab the latest version of the library

    $ go get github.com/pulumi/pulumi-dnsimple/sdk/go/...

## Configuration

The following configuration points are available:

- `dnsimple:token` - (required) The address for the dnsimple server connection.
- `dnsimple:account` - (required) The port for the dnsimple server connection. The default is 5432.

## Reference

For detailed reference documentation, please visit [the API docs](https://pulumi.io/reference/pkg/nodejs/@pulumi/dnsimple/index.html).
