# Ystia Forge Changelog

## UNRELEASED

### NEW COMPONENTS

* SSL Certificates Generator component ([GH-78](https://github.com/ystia/forge/issues/78))
* Deploy Docker containers in pure TOSCA ([GH-76](https://github.com/ystia/forge/issues/76))
* Docker Registry ([GH-80](https://github.com/ystia/forge/issues/80))

### ENHANCEMENTS

* Update forge components installing/configuring Yorc to support python3 ([GH-85](https://github.com/ystia/forge/issues/85))
* Update Ansible version to 2.7.9 ([GH-83](https://github.com/ystia/forge/issues/83))
* Add a vault in secured full stack topology ([GH-67](https://github.com/ystia/forge/issues/67))
* Provide forge components/topology allowing to install a secured Yorc setup ([GH-37](https://github.com/ystia/forge/issues/37))

### DEPENDENCIES

* Ystia Forge components require now Alien4Cloud 2.1.1 ([GH-64](https://github.com/ystia/forge/issues/64))
* Ystia Forge components require now Alien4Cloud CSAR public library 2.2.0-SNAPSHOT
* Ystia Forge components require now yorc-types 1.1.0 (GH-82](https://github.com/ystia/forge/pull/82))

### BUG FIXES

* Install a newer version of Anaconda (Python Component) in order to fix dependencies issues ([GH-69](https://github.com/ystia/forge/issues/69))
* Several wrong version referenced for csar-public-lib components ([GH-58](https://github.com/ystia/forge/issues/58))
* Jupyter depends on EPEL repository but do not ensure that it is installed ([GH-70](https://github.com/ystia/forge/issues/70))

## 2.1.0 (December 20, 2018)

### BUG FIXES

* Kafka download URLs no more valid ([GH-41](https://github.com/ystia/forge/issues/41))
* Types definition issues detected when uploading forge github repository in Alien4Cloud ([GH-42](https://github.com/ystia/forge/issues/42))
* Forge components installing dnsmaq fail on RHEL 7.5  ([GH-44](https://github.com/ystia/forge/issues/44))

### DEPENDENCIES

* Ystia Forge components require now Alien4Cloud 2.1.0
* Ystia Forge components require now Alien4Cloud CSAR public library 2.1.0

## 2.1.0-RC1 (December 17, 2018)

### DEPENDENCIES

* Ystia Forge components require now Alien4Cloud 2.1.0-RC1
* Ystia Forge components require now Alien4Cloud CSAR public library 2.1.0-RC1

### BUG FIXES

* Component NFS Client fails to mount directory exported by NFS server on GCP ([GH-38](https://github.com/ystia/forge/issues/38))

## 2.1.0-M7 (December 07, 2018)

### NEW FEATURES

* Provide Consul components/topology allowing to install a secured Consul setup ([GH-28](https://github.com/ystia/forge/issues/28))
* Support of Yorc bootstrap ([GH-32](https://github.com/ystia/forge/issues/32))

### IMPROVEMENTS

* TerraformRuntime component should have a download URL in argument ([GH-22](https://github.com/ystia/forge/issues/22))

## 2.1.0-M6 (November 16, 2018)

### DEPENDENCIES

* Ystia Forge components require now Alien4Cloud 2.1.0-SM7
* Ystia Forge components require now Alien4Cloud CSAR public library 2.1.0-SM7

### BUG FIXES

* Yorc AnsibleRuntime component creation fails on CentOS 7 on AWS ([GH-30](https://github.com/ystia/forge/issues/30))


## 2.1.0-M5 (October 26, 2018)

### NEW COMPONENTS

* Google Compute Engine Infrastructure configuration ([GH-23](https://github.com/ystia/forge/issues/23))

## 2.1.0-M4 (October 08, 2018)

### DEPENDENCIES

* Ystia Forge components require now Alien4Cloud 2.1.0-SM6
* Ystia Forge components require now Alien4Cloud CSAR public library 2.1.0-SM6

### NEW COMPONENTS

* Slurm scheduler and its dependencies ([GH-20](https://github.com/ystia/forge/issues/20)):
  * NTP
  * Dnsmasq
  * Resolvconf
  * Munge

### IMPROVEMENTS

* Ystia Forge Consul components at org/ystia/experimental/consul/ install now Consul 1.2.3
