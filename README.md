# CasaOs Resources
My personal list of Docker Compose files, for building cutom containers on CasaOs.

## Volume Mapping
These all use MY personal VOLUME mapping, and should you wish to use these compose files, I suggest that you change the mapping.

e.g. I use my personally mounted drive `/mnt/Storage1_nvme0n1p1`, so remove this sub-string from the `source` mounting, if you want to use the default.

## How to install on CasaOs
1. Go to the CasaOs desktop
1. Click on `App Store`
1. Click on `Custom Install`, in the top right
1. Click on the `Custom Install` icon, in the top right
1. In the `Import` dialog, in the `Docker Compose` tab, paste the raw `YML` file content.
1. Click on the `Submit` button.
1. Complete any additional information the import may require.