# Prerequisites
Go to https://github.com/pilif42/githubActionPoc/settings/secrets/actions
Add Environment secrets:
    - env = dev: TSANDCS_HOST, TSANDCS_SSH_USER & TSANDCS_SSH_PASSWORD
    - same thing for env = test


# Workflow
Defined in .github/workflows/poc.yml

Inspired from:
    - https://github.com/pandoc/pandoc-action-example/blob/master/.github/workflows/advanced.yml
    - https://docs.github.com/en/free-pro-team@latest/actions/guides/storing-workflow-data-as-artifacts



