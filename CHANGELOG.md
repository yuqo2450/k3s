# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [v0.1.0] - 2023-10-02

### Changed

* Added role prefix to variable names
* Updated to k3s version v1.28.2
* Changed variable name server to lb_ip
* Cluster join is not done with kube-vip lb ip anymore
* Renamed config files
* Init config file is now overriden by default

### Added

* Documentation of collection and roles
* Handler to restart k3s when configuration is changed
* Changelog
* Github actions
  * To run linting on pull request
  * To create new release for each tag

[v0.1.0]: https://github.com/yuqo2450/ans-k3s/compare/v0.1.0
