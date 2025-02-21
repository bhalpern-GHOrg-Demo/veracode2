<img src="imgs/vclogo-light-mode.png#gh-light-mode-only">
<img src="imgs/vclogo-dark-mode.png#gh-dark-mode-only">

## Veracode GitHub Workflow Integration 
> Warning, this is a modified version of the Veracode GitHub App
> The current version and version information compared to the GitHub App is at the bottom of the README in the version section
> If you make any changes to the .github workflow files, then the app will cease to get updates from the upstream. In order to resolve this, see the [`update-workflow.yml`](.github/update-workflow.yml) workflow that runs at a cadence similiar to the [`update-cli.yml`](.github/update=cli.yml) in order to make sure that the veracode workflow app is the most up to date


The Veracode GitHub Workflow Integration allows you to set up a security scanning program for all of your GitHub repositories in a single configuration file.

This repository includes the workflows required for the GitHub Workflow Integration to function correctly. In addition, it includes the configuration file, `veracode.yml`, which stores the default settings for you to scan your repositories with Veracode.

For guidance on installing the Veracode Workflow Application and additional information about the integration, please view the Veracode documentation.
https://docs.veracode.com/r/GitHub_Workflow_Integration_for_Repo_Scanning

