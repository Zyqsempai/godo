# Change Log

## Unreleased

- #250 Add Kubernetes GetUser method - @snormore

## [v1.19.0] - 2019-07-19

- #244 dbaas: add private-network-uuid field to create request

## [v1.18.0] - 2019-07-17

- #241 Databases: support for custom VPC UUID on migrate @mikejholly
- #240 Add the ability to get URN for a Database @stack72
- #236 Fix omitempty typos in JSON struct tags @amccarthy1

## [v1.17.0] - 2019-06-21

- #238 Add support for Redis eviction policy in Databases @mikejholly

## [v1.16.0] - 2019-06-04

- #233 Add Kubernetes DeleteNode method, deprecate RecycleNodePoolNodes @bouk

## [v1.15.0] - 2019-05-13

- #231 Add private connection fields to Databases - @mikejholly
- #223 Introduce Go modules - @andreiavrammsd

## [v1.14.0] - 2019-05-13

- #229 Add support for upgrading Kubernetes clusters - @adamwg

## [v1.13.0] - 2019-04-19

- #213 Add tagging support for volume snapshots - @jcodybaker

## [v1.12.0] - 2019-04-18

- #224 Add maintenance window support for Kubernetes- @fatih

## [v1.11.1] - 2019-04-04

- #222 Fix Create Database Pools json fields - @sunny-b

## [v1.11.0] - 2019-04-03

- #220 roll out vpc functionality - @jheimann

## [v1.10.1] - 2019-03-27

- #219 Fix Database Pools json field - @sunny-b

## [v1.10.0] - 2019-03-20

- #215 Add support for Databases - @mikejholly

## [v1.9.0] - 2019-03-18

- #214 add support for enable_proxy_protocol. - @mregmi

## [v1.8.0] - 2019-03-13

- #210 Expose tags on storage volume create/list/get. - @jcodybaker

## [v1.7.5] - 2019-03-04

- #207 Add support for custom subdomains for Spaces CDN [beta] - @xornivore

## [v1.7.4] - 2019-02-08

- #202 Allow tagging volumes - @mchitten

## [v1.7.3] - 2018-12-18

- #196 Expose tag support for creating Load Balancers.

## [v1.7.2] - 2018-12-04

- #192 Exposes more options for Kubernetes clusters.

## [v1.7.1] - 2018-11-27

- #190 Expose constants for the state of Kubernetes clusters.

## [v1.7.0] - 2018-11-13

- #188 Kubernetes support [beta] - @aybabtme

## [v1.6.0] - 2018-10-16

- #185 Projects support [beta] - @mchitten

## [v1.5.0] - 2018-10-01

- #181 Adding tagging images support - @hugocorbucci

## [v1.4.2] - 2018-08-30

- #178 Allowing creating domain records with weight of 0 - @TFaga
- #177 Adding `VolumeLimit` to account - @lxfontes

## [v1.4.1] - 2018-08-23

- #176 Fix cdn flush cache API endpoint - @sunny-b

## [v1.4.0] - 2018-08-22

- #175 Add support for Spaces CDN - @sunny-b

## [v1.3.0] - 2018-05-24

- #170 Add support for volume formatting - @adamwg

## [v1.2.0] - 2018-05-08

- #166 Remove support for Go 1.6 - @iheanyi
- #165 Add support for Let's Encrypt Certificates - @viola

## [v1.1.3] - 2018-03-07

- #156 Handle non-json errors from the API - @aknuds1
- #158 Update droplet example to use latest instance type - @dan-v

## [v1.1.2] - 2018-03-06

- #157 storage: list volumes should handle only name or only region params - @andrewsykim
- #154 docs: replace first example with fully-runnable example - @xmudrii
- #152 Handle flags & tag properties of domain record - @jaymecd

## [v1.1.1] - 2017-09-29

- #151 Following user agent field recommendations - @joonas
- #148 AsRequest method to create load balancers requests - @lukegb

## [v1.1.0] - 2017-06-06

### Added
- #145 Add FirewallsService for managing Firewalls with the DigitalOcean API. - @viola
- #139 Add TTL field to the Domains. - @xmudrii

### Fixed
- #143 Fix oauth2.NoContext depreciation. - @jbowens
- #141 Fix DropletActions on tagged resources. - @xmudrii

## [v1.0.0] - 2017-03-10

### Added
- #130 Add Convert to ImageActionsService. - @xmudrii
- #126 Add CertificatesService for managing certificates with the DigitalOcean API. - @viola
- #125 Add LoadBalancersService for managing load balancers with the DigitalOcean API. - @viola
- #122 Add GetVolumeByName to StorageService. - @protochron
- #113 Add context.Context to all calls. - @aybabtme
