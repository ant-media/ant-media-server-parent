# ant-media-server-parent

Parent POM-only project used by many other projects in the organization.

## Releasing

Pull requests created on branches (e.g. `feature/foo`) deploy a snapshot version with name `4.0.0-foo-SNAPSHOT`

Tag pushes on the `master` branch using this pattern: `ams-v4.0.0` trigger a non-snapshot deployment.