# Mintmaker Config for Conforma

This repository contains an [inherited configuration](https://konflux-ci.dev/docs/mintmaker/user/#inherited-config) for [Konflux Mintmaker](https://github.com/konflux-ci/mintmaker). This configuration extends and overrides the [default Mintmaker configuration for Konflux](https://github.com/konflux-ci/mintmaker/blob/main/config/renovate/renovate.json), and is shared among all the repositories in the Conforma organization.

## About Mintmaker

Mintmaker is a Konflux project that automates dependency checking and updating for components using [Renovate](https://docs.renovatebot.com/). It introduces the `DependencyUpdateCheck` custom resource to trigger dependency update processes across Konflux components on GitHub and GitLab platforms.

## Contributing

To modify this shared configuration, please create a pull request with your proposed changes. Consider the impact on all repositories that inherit from this configuration.