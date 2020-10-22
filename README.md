# c9-staroid
Cloud9 on Staroid 🌟🌟

[![Run](https://staroid.com/api/run/button.svg)](https://staroid.com/api/run)

## About

This Staroid project is a Staroid deployment manifest to the existing [Cloud9 On OpenShift](https://github.com/ClarityCafe/cloud9-on-openshift) repository. 
The following can be deployed in Skaffold as well to test the changes.

## Which branch to deploy?

Currently there are two branches you can deploy at the moment, both are maintained.

- `v2`: This is the original v2 code from Cloud9 Inc. It is in GPLv3 and currently it's maintained by the commmunity as a fork. This is the only FOSS Cloud9 IDE in existence.

- `v3`: This is the Cloud9 IDE you've grown to love until 2019 when it was bought by Amazon. It is now current known as AWS Cloud9. The IDE's is a snapshot of the now defunct PaaS from Cloud9 Inc, which is used for SDK development - and is functionally similar to AWS Cloud9.

You can deploy either version but do keep in mind:

- For v2: We are using CentOS 8 with PowerTools enabled. Only a bare minimum of build dep essentials are installed.
- For v3: We are using CentOS 7, with a handful of packages. You will have to install some build deps yourself.

## Disclaimer

Cloud9 IDE is a trademark of Cloud9 Inc. (Now Amazon Web Services). V2 code is Licensed under GPLv3. The V3 code is intended for non-commercial development purposes only. I (Ayane Satomi) are in no way related to AWS. 