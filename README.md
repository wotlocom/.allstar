# Allstar configuration for GoogleContainerTools

[Allstar](https://github.com/ossf/allstar) is a security-policy GitHubApp. It is
installed on this org, and this repo contains the configuration for that app. It
is configured to create issues on repos that do not comply with the configured
policy.

## Enabled Repos

Allstar is configured in opt-in. [See here for the list of enabled repos](allstar.yaml). Feel
free to submit a PR to enable/disable repos.

## Policy Configuration
These are the expected settings to be in compliance

### [Branch Protection](branch_protection.yaml)

|-|-|
| Require approval | yes |
| Approvals required | 1 |
| Dismiss stale reviews | not required |
| Block force push | yes |