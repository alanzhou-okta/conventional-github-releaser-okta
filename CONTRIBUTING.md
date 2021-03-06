#Contributing to Okta Open Source Repos

## Style

### Git Commit Messages

We use a simplified form of [Atom](https://github.com/atom/atom/blob/master/CONTRIBUTING.md#git-commit-messages) commit convention.

  * Use the present tense ("Add feature" not "Added feature")
  * Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
  * Limit the first line to 72 characters or less
  * Add one feature per commit. If you have multiple features, have multiple commits.
  
####Template

    <emoji> Short Description of Commit
    <BLANKLINE>
    More detailed description of commit
    <BLANKLINE>
    Resolves: <Jira # or Issue #>

#### Emoji Categories
Our categories include:
  * :package: `:package` when pushing new release
  * :art: `:art:` when improving the format/structure of the code
  * :seedling: `:seedling`: when creating a new feature
  * :memo: `:memo:` when writing docs
  * :bug: `:bug:` when fixing a bug
  * :fire: `:fire:` when removing code or files
  * :white_check_mark: `:white_check_mark:` when adding tests
  * :arrow_up: `:arrow_up:` when upgrading dependencies
  * :arrow_down: `:arrow_down:` when downgrading dependencies
    
If you do not see an exact emoji match, use the best matching emoji.

#### Example
    📝 Update CONTRIBUTING.md

    Update Contributing.md with new emoji categories
    Update Contributing.md with new template 
    
    Resolves: OKTA-12345

