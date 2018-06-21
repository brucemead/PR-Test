## Please, go through these steps before you submit a PR.

1. Make sure that your PR is not a duplicate.
2. If not, then make sure that:

  2.1. You **MUST** do your changes in a separate branch.
  
  2.2. Branches **MUST** have:
  
  2.2.1. Descriptive names
  
  2.2.2. Include a valid JIRA ticket key
  
  2.2.3. Start with either the `fix/`, `patch/`, `hotfix/`, `upgrade/`, `release/` or `feature/` prefixes. Good examples are: `fix/sla-2444-less-compilation-by-adding-missing-variable`, `feature/sla-2443-add-new-blog-module` or `upgrade/sla-2445-upgrage-to-magento-2.2.4`.

Branch Prefix | Purpose
--- | ---
`feature/` | I'm adding a new feature or expanding on an existing one.
`fix/` | I'm fixing an issue with an existing feature or existing code.
`patch/` | I'm introducing a new patch, this could be one of our own standard patches or a Magento SUPEE patch.
`upgrade/` | Upgrading the core application version.
`hotfix/` | This is for any fixes that will enter an expedited workflow and potentially get merged directly to `master`.
`release/` | This is replacing merging directly to `master` and is used to prepare all the above for deployment release. No work should be undertaken in this branch directly. These branch should only be created by deployers.

  2.2. You **MUST** have a descriptive commit message with a short title (first line) that includes a valid JIRA ticket key.

  2.3. You **MUST** successfully run related build commands `php bin/magento setup:di:compile` or `php bin/magento setup:di:compile`
  
  2.4. You **MUST** label your PR with either `Frontend` or `Backend` or both depending on whats within the PR and which members of which teams need to review the works.
  
3. **After** these steps, you're ready to open a pull request.

  3.1. Your pull request **MUST NOT** target the `master` branch on this repository.
  
  3.2. You **MUST** ensure your branch has first been PR'd and tested on `development` and then `staging`.

  3.2. **Title to your PR** clearly for the changes presented.

  3.3. **Detailed description** of your changes and references to all JIRA tickets relating to the commits.

**PLEASE REMOVE THIS TEMPLATE BEFORE SUBMITTING**

Thank you!
:muscle: :heart:
