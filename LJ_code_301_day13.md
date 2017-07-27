# Code 301, day 13

### Deployment
- Deployment vs Production, deploy doesn't have to mean put into production, you can deploy without putting into production.
- Can deploy each pull request on master, or can do things like making pull requests to a dev branch and then pull requests from the dev branch into master, can even pull out separate pieces to demos.  Either way is fine, but be consistent.
- Try to keep master always 'finished' as in it always has working as is code.
- When you need more complexity, you can have even more branches you push/pull to like feature branches, a development branch, release branches, hotfixes, and a master branch.
- Loose coupling - remove dependencies unless you absolutely need them.  Try to have each piece not require other pieces. Example Handlebars.js and jQuery, they work together fine, but you could replace or remove either piece and not break the other. Contract between pieces should stay the same, but you can change the pieces as long as you keep the contract the same.
- semver.org  Semantic Versioning.  1.0.0  first is breaking changes, 2nd has feature changes, 3rd is bugfixes.
