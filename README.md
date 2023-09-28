# uds-package-external-dns

Zarf package for use in UDS bundle to deploy [External-DNS](https://kubernetes-sigs.github.io/external-dns/latest/)

### Install

This package installs the external-dns namespace and deployment resources as a helm release, using Ironbank images.

## Controlling Values

Zarf variables, preferrably via a [zarf-config.yaml](zarf-config.yaml) should be used to provide the necessary inputs for this package.

## Order of Operations

We recommend you deploy external-dns after DUBBD.

