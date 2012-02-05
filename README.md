# FGA Profile

This is the main repository for the Drupal distribution component of the 
Federated General Assembly (a working title) project. It has the
following structure:

## Directory layout

This repository combines a few logical layers of the overall stack - some
Drupal-internal components with some meta-Drupal logic - into a
single repository in order to ease management and development.

```
  deploy/ # contains deployment build scripts
  test/ # contains both Drupal and FGA node-level automated tests
  fga.make # the drush makefile specifying the project components
  fga.profile # the Drupal installation profile's main file.
  fga.install # the Drupal installation profile's install file.
  fga.info # the Drupal installatino profile's info file.
  modules/ # modules contained in the installation profile.
  themes/ # themes contained in the installation profile.
```

The alternative is an awkward application of submodules or another
subtree merging strategy, which are still difficult enough for most Git
users that they constitute an unnacceptably high barrier to entry.

## Versioning consistency

## Development practices
