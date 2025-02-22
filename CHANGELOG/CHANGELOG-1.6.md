# v1.6.1 - Changelog since v1.6.0

## Changes by Kind

### Bug or Regression

- Update go version to 1.20.6 to fix CVE-2023-29406 ([#576](https://github.com/kubernetes-sigs/gcp-filestore-csi-driver/pull/576), [@k8s-infra-cherrypick-robot](https://github.com/k8s-infra-cherrypick-robot))

# v1.6.0 - Changelog since v1.5.6

## Changes by Kind

### Feature

- CMEK support now won't be checked in the CSI driver, trying to create basic or premium tier instances with cmek will result in invalid argument error from the Filestore API.

  high scale tier instance creation with IP reservation is now supported ([#563](https://github.com/kubernetes-sigs/gcp-filestore-csi-driver/pull/563), [@leiyiz](https://github.com/leiyiz))

### Uncategorized

- Add labels to backups created through the driver ([#561](https://github.com/kubernetes-sigs/gcp-filestore-csi-driver/pull/561), [@hsadoyan](https://github.com/hsadoyan))

## Dependencies

_Nothing has changed._
