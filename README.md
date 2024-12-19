Github action workflow to automate semantic versioning and update changelogs and release notes automatically.

It created a versioning system as follows,
`v<major>.<minor>.<patch>`

To be able to automate the semantic versioning you must start the commits with:

- feat: or fix: and `BREAKING CHANGE`: major change, not backwards compatible (major)
- `feat:` new feature, backwards compatible (minor)
- `fix:`fix to a certain feature, backwards compatible (patch)
