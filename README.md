# Example of Using the GitHub API to Get a Repository's Clone, Fork, and View Count

1. `npm install`
1. Open `repoStats.js` and add your Github personal token at the top. https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
1. Add your `owner` and `repo` values into the `ownersRepos` array. For example, `danwahlin` is my owner value and `angular-jumpstart` could be a repo.
1. Save `repoStats.js`. 
1. Run `node repoStats.js`

*NOTE* You must have pull access to a repository for this to work correctly.