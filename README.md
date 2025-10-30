# Allstar configuration for Wotlocom

[Allstar](https://github.com/ossf/allstar) is a security-policy GitHubApp. It is
installed on this org, and this repository contains the configuration for that app. It
is configured to create issues on repos that do not comply with the configured
policy.

## Enabled Repos

Allstar is configured in opt-in. [See here for the list of enabled repos](allstar.yaml). Feel
free to submit a PR to enable/disable repos.

## Policy Configuration

These are the expected settings to be in compliance

### [Branch Protection](branch_protection.yaml)

|                       |              |
| --------------------- | ------------ |
| Branches enforced     | default      |
| Require approval      | yes          |
| Approvals required    | 1            |
| Dismiss stale reviews | not required |
| Block force push      | yes          |

### [Binary Artifacts](binary_artifacts.yaml)

- Binary artifacts not allowed.

### [Outside Collaborators](outside.yaml)

- Push access allowed.
- Admin access not allowed.

## Security

Please read [SECURITY.md](SECURITY.md) for details on our security policy and how to report security vulnerabilities.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## Code of Conduct

Please read [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for details on our code of conduct.

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
