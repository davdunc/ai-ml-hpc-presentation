
# Table of Contents

1.  [Analytis at the Edge of the Data Lake with OpenDataHub and OpenShift](#orgce092e0)
2.  [Build Project](#orge4b662c)
    1.  [Build out Infrastructure Support](#org9a5810e)
    2.  [Build the test Data Lake](#orgb21fa5f)


<a id="orgce092e0"></a>

# Analytis at the Edge of the Data Lake with OpenDataHub and OpenShift

This repository is a design to build a small test Data Lake
using public data and then demonstrate solutions built using the
open source


<a id="orge4b662c"></a>

# Build Project

This project uses Ansible to build out the infrastructure.


<a id="org9a5810e"></a>

## Build out Infrastructure Support

This is the part of the project that supports the build. It doesn't
create the component parts, but without these essential elements,
we wouldn't have access to the project at all.

-   [ ] Build the IAM Users for initial management
-   [ ] Build the IAM Roles for the initial instance configuration


<a id="orgb21fa5f"></a>

## Build the test Data Lake

This is the first story, but the motivation for the use of the test
data was a general interest in things oceanic and limnologic. I
would prefer to use a freshwater limnology. I just haven't found it
yet. We are using data from the Multi-Scale Ultra high Resolution
Sea Surface data set.

How to cite the database access:

> Multi-Scale Ultra High Resolution (MUR) Sea Surface Temperature (SST) was accessed on DATE from <https://registry.opendata.aws/mur>.

How to access the content of the Open Data set:

    aws s3 ls s3://mur-sst/zarr/ --no-sign-request

