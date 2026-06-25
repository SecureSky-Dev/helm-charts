# Soveren Ranger for Data-At-Rest (DAR) Sensor releases

There are the following components of Ranger:

| Component  | Kind       | Name     |
|------------|------------|----------|
| **Ranger** | Deployment | `ranger` |


Below are the release notes for the latest versions of Ranger. There is also the Helm chart version for each release.

## Secure Sky DAR Ranger release

Release date: Jun 25, 2026

### Versions

* **Ranger**: 0.20.0
* **Helm chart**: 0.19.0

Moving DAR ranger to Secure Sky images.

## Ranger-24.9.2

Release date: Sep 30, 2024

### Versions

* **Ranger**: 0.10.0
* **Helm chart**: 0.18.0

### Changes

In this release, we've introduced a new approach to working with databases via the new Ranger component. It can be launched and granted access to the database. Once initialized, it establishes communication with the [Crawler](https://github.com/SecureSky-Dev/helm-charts/tree/master/charts/soveren-dar-sensor), allowing the Crawler to delegate database processing tasks to Ranger without requiring access credentials for the database.

#### Ranger v0.10.0

* Initial release.
