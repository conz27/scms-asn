# scms-asn

This repository contains the ASN.1 definitions for data containers and protocols
used in SCMS.

## Initializing the Git Repository

It's important to note that this repository contains a Git submodule (i.e. a
dependency on the 1609.2 public repository). Therefore, doing a simple Git
clone is not enough to pull down the entire repo.

Instructions to clone the SCMS-ASN repository are as follows:

1. ```git clone http://<username>@stash.campllc.org/scm/scms/scms-asn.git```, where 
```<username>``` is your CAMP login.

2. Go into the scms-asn folder and run ```git submodule update --init --recursive``` 
to checkout the 1609.2 repository.

OSS provides an online playground to verify your ASN.1, encode/decode data at http://asn1-playground.oss.com/.
In Windows open a command line, change into the scms-asn directory and type 
```type 1609dot2-asn\1609dot2-schema.asn 1609dot2-asn\1609dot2-base-types.asn 1609dot2-asn\crl-base-types.asn 1609dot2-asn\crl-protocol.asn 1609dot2-asn\crl-ssp.asn  component-cert-management-errors.asn component-cert-management.asn scms-base-types.asn cert-chain-files.asn scms-policy.asn scms-common-errors.asn eca-ee-errors.asn eca-ee.asn ee-ma.asn ee-ra.asn la-ma-errors.asn la-ma.asn la-pca-errors.asn la-pca.asn la-ra-errors.asn la-ra.asn ma-pca-errors.asn ma-pca.asn ma-ra-errors.asn ma-ra.asn pca-ra-errors.asn pca-ra.asn ra-pg-errors.asn ra-pg.asn scms-error.asn scms-protocol.asn cert-profile.asn > scms.asn.txt``` 
to create a single file for upload to the OSS Playground. You know what to do in Linux ;-)