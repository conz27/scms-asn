# scms-asn

This repository contains the ASN.1 definitions for data containers and protocols
used in SCMS.

## Initializing the Git Repository

It's important to note that this repository contains a Git submodule (i.e. a
dependency on the 1609.2 public repository). Therefore, doing a simple Git
clone is not enough to pull down the entire repo.

Instructions to clone the SCMS-ASN repository are as follows:

1. ```git clone http://<username>@stash.campllc.org/scm/scms/scms-asn.git```, where 
'<username>' is your CAMP login.

2. Go into the scms-asn folder and run ```git submodule update --init --recursive``` 
to checkout the 1609.2 repository.

