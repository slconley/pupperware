# Change Log

This file documents all notable changes to Puppet Server Helm Chart. The release
numbering uses [semantic versioning](http://semver.org).

NOTE: The change log until version `v0.2.4` is auto-generated.

## [v1.6.1](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.6.1) (2019-12-31)

- Add comments in Values file for Puppetserver Service.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.6.0...v1.6.1)

## [v1.6.0](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.6.0) (2019-12-26)

- Add optional affinity for "r10k" pod assignment.
- File permission fixes for "r10k" jobs' SSH keys.
- Security fixes for the "r10k" jobs.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.5.3...v1.6.0)

## [v1.5.3](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.5.3) (2019-12-09)

- Small README fixes.
- Add information about the chart in the main [README.md](https://github.com/puppetlabs/pupperware/blob/master/README.md) of Puppetlabs's Pupperware repo.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.5.2...v1.5.3)

## [v1.5.2](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.5.2) (2019-12-06)

- Fix PuppetDB usage of pre-generated Puppet SSL certs.
- Increase deadline time for Puppet pre-install job.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.5.1...v1.5.2)

## [v1.5.1](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.5.1) (2019-12-03)

- Small Indentation Fixes.
- Use Recommended Dir for PostreSQL's PGDATA.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.5.0...v1.5.1)

## [v1.5.0](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.5.0) (2019-12-02)

- Fixes and additions to setting SSH credentials from existing K8s secret.
- Create separate r10k jobs/schedules for Control Repo and Hiera Data.
- Place r10k cache on PVC.
- Deprecate HTTPS authentication.
- Indentation corrections.
- General code clean-up.
- Updates to README.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.4.0...v1.5.0)

## [v1.4.0](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.4.0) (2019-11-28)

- Add optional usage of pre-generated Puppet SSL certificates.
- Use default path for eYaml keys.
- Small Values file comment fixes.
- Code clean-up and lint fixes.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.3.1...v1.4.0)

## [v1.3.1](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.3.1) (2019-11-25)

- Small Values file fix.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.3.0...v1.3.1)

## [v1.3.0](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.3.0) (2019-11-25)

- [Firewall Related] Add support for separate r10k network protocols to gather the code of Puppet and Hiera repos.
- Increase default r10k sync runtime interval to every 5 minutes.
- Syntax improvements.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.2.2...v1.3.0)

## [v1.2.2](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.2.2) (2019-11-24)

- Fixes <https://github.com/puppetlabs/pupperware/issues/187> and <https://github.com/puppetlabs/pupperware/issues/188.>
- `r10k` now runs with the `puppet` username and group id - meaning all the files in `/etc/puppetlabs` are now owned by Puppet Server.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.2.1...v1.2.2)

## [v1.2.1](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.2.1) (2019-11-22)

- Fixes for "r10k" extra container args.
- Values file small fixes.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.2.0...v1.2.1)

## [v1.2.0](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.2.0) (2019-11-21)

- Add optional extra container environment variables.
- Add optional "r10k" extra container arguments.
- Bump PupptDB to v6.7.3.
- Small code indentation improvements.
- README updates.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.1.0...v1.2.0)

## [v1.1.0](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.1.0) (2019-11-19)

- Switch Pulling the Hiera Data Repo from Using "git_sync" to "r10k".

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.0.1...v1.1.0)

## [v1.0.1](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.0.1) (2019-11-11)

- Fix Permissions for Hiera, Puppet Server and eYaml Configs.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v1.0.0...v1.0.1)

## [v1.0.0](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v1.0.0) (2019-11-08)

- Differentiate "nodeSelector" for Pods with Common Storage.
- Fix for PostgreSQL on AWS.
- Small Syntax and Indentation Fixes.
- Improve README.
- Improve Values Comments.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v0.3.5...v1.0.0)

## [v0.3.5](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v0.3.5) (2019-10-31)

- Add Optional `selector` for PVs/PVCs.
- Switch to Apache v2.0 License.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v0.3.4...v0.3.5)

## [v0.3.4](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v0.3.4) (2019-10-28)

- Add Ingress.
- Improve Tmpl Helpers.
- Improve `NOTES`.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v0.3.3...v0.3.4)

## [v0.3.3](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v0.3.3) (2019-10-27)

- Add Optional Static Data Volumes.
- Add Configurable PVC's Size.
- Add Optional PVC's Annotations.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v0.3.2...v0.3.3)

## [v0.3.2](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v0.3.2) (2019-10-26)

- Add optional extra Pod Annotations.
- Add optional Pod Priority Scheduling.
- Add LICENSE.
- Add CHANGELOG.
- Update README.
- Fixes.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v0.3.1...v0.3.2)

## [v0.3.1](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v0.3.1) (2019-10-24)

- Add optional "nodeSelector", "affinity" and "tolerations" for Pod Deployments.
- Improve Values Comments.
- Bump Component Versions.

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v0.2.4...v0.3.1)

## [v0.2.4](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v0.2.4) (2019-10-12)

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v0.2.3...v0.2.4)

## [v0.2.3](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v0.2.3) (2019-10-11)

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v0.2.2...v0.2.3)

## [v0.2.2](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v0.2.2) (2019-10-09)

[Full Changelog](https://github.com/Xtigyro/puppetserver-helm-chart/compare/v0.2.0...v0.2.2)

## [v0.2.0](https://github.com/Xtigyro/puppetserver-helm-chart/tree/v0.2.0) (2019-09-20)

\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*
